# HOWTO Contribute

## Setup

Many files in this repository are autogenerated by [scripts/generate](scripts/generate).
Those files are not intended to be modified manually, rather underlying scripts
and/or configuration should be adjusted to either update or produce new files.
In particular `generate` produces

- [.github/workflows/test-datalad_*.yaml](.github/workflows/) - GitHub workflows
  to test **released** versions of the extensions against **master** branch of
  DataLad.  The rationale: DataLad master branch CI tests against **master**
  branch of extensions, so we could coordinate ongoing development of DataLad
  and its extensions
- [README.md](README.md) - a "dashboard" representing health status
  (status of testing, currently released versions availability, etc).

### [extensions.yaml](extensions.yaml)

This file provides `generate` script a specification for which extensions to
produce the GitHub workflows from the
[templates/.github/workflows/test-{{extension.name}}.yaml](templates/.github/workflows/test-{{extension.name}}.yaml) template.
This file expects a dictionary with the key `extensions` which should be a list
of extension package names with following optional fields:

- `apt_depends` - additional Debian packages to be installed using `apt`
- `pypi` - name of the pypi package, if it is different from the name
- `conda` - name of the conda package, if it is different from the name
- `github` - name of the repository if it is different from the name. If this
  contains a `/` it is expected to contain the organization otherwise it's 
  assumed to be under `datalad/` organization on Github.
- `tester` - what test framework to use. Currently either 'nose' or 'pytest'; 
  defaults to 'nose'. Used to generate `.travis.yml`
- `ci` - name of the CI system to link to for showing an extension's master vs
  Datalad released CI build. Currently recognizes 'Travis' and 'AppVeyor'
  (case-insensitive)
- `ci-user` - name of the user under which CI is running. Currently only needed
  for AppVeyor since the link to CI builds depends on it

## HOWTO re-generate files

Majority of the invocations of `generate` are tracked using `datalad run`.
After you introduce your changes to either `extensions.yaml` or `generate`,
commit your changes and either run `datalad rerun generate`
(there is a `generate` tag) or just `make` which would run it for you.
