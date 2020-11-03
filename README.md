# DataLad healthchecks

This is a "dashboard" of various CIs of DataLad, its extensions, and underlying
3-rd party projects like git-annex.

**This README.md is autogenerated - do not edit.
  See [CONTRIBUTING.md](CONTRIBUTING.md) for more information.**

## Git-annex Status

 - Conda: ![Conda?](https://anaconda.org/conda-forge/git-annex/badges/version.svg)
    ![Updated](https://anaconda.org/conda-forge/git-annex/badges/latest_release_relative_date.svg)
    ![Platforms?](https://anaconda.org/conda-forge/git-annex/badges/platforms.svg)
 - Current snapshot build/tests + DataLad tests:
    [![Build git-annex snapshot on Ubuntu](https://github.com/datalad/git-annex/workflows/Build%20git-annex%20on%20Ubuntu/badge.svg)](https://github.com/datalad/git-annex/actions?query=workflow%3A%22Build+git-annex+on+Ubuntu%22)
    [![Build git-annex snapshot on macOS](https://github.com/datalad/git-annex/workflows/Build%20git-annex%20on%20macOS/badge.svg)](https://github.com/datalad/git-annex/actions?query=workflow%3A%22Build+git-annex+on+macOS%22)
    [![Build git-annex snapshot on Windows](https://github.com/datalad/git-annex/workflows/Build%20git-annex%20on%20Windows/badge.svg)](https://github.com/datalad/git-annex/actions?query=workflow%3A%22Build+git-annex+on+Windows%22)

## DataLad Status

 [![DataLad GitHub release](https://img.shields.io/github/release/datalad/datalad.svg)](https://GitHub.com/datalad/datalad/releases/)
 [![DataLad PyPI version fury.io](https://badge.fury.io/py/datalad.svg)](https://pypi.python.org/pypi/datalad/)
 ![Conda?](https://anaconda.org/conda-forge/datalad/badges/version.svg)
 - CI:
   [![Travis tests status](https://secure.travis-ci.org/datalad/datalad.png?branch=master)](https://travis-ci.org/datalad/datalad)
   [![Build status](https://ci.appveyor.com/api/projects/status/github/datalad/datalad?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad/branch/master)
   [![Documentation](https://readthedocs.org/projects/datalad/badge/?version=latest)](http://datalad.rtfd.org)
 - Misc:
   [![codecov.io](https://codecov.io/github/datalad/datalad/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad?branch=master)

## DataLad Extensions Status

 | Name | Release | PyPI Release | Conda Release | CI: Released + DL master | CI: master + DL Release | Codecov | Issue Resolution | Open Issues | 
 | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
 | [datalad_neuroimaging](https://github.com/datalad/datalad-neuroimaging) | [![?](https://img.shields.io/github/release/datalad/datalad-neuroimaging.svg)](https://GitHub.com/datalad/datalad-neuroimaging/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad_neuroimaging.svg)](https://pypi.python.org/pypi/datalad_neuroimaging/) | ![-](https://anaconda.org/conda-forge/datalad-neuroimaging/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_neuroimaging/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_neuroimaging) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-neuroimaging.png?branch=master)](https://travis-ci.org/datalad/datalad-neuroimaging) | [![codecov.io](https://codecov.io/github/datalad/datalad-neuroimaging/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-neuroimaging?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-neuroimaging.svg)](http://isitmaintained.com/project/datalad/datalad-neuroimaging "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-neuroimaging.svg)](http://isitmaintained.com/project/datalad/datalad-neuroimaging "Percentage of issues still open") | 
 | [datalad_container](https://github.com/datalad/datalad-container) | [![?](https://img.shields.io/github/release/datalad/datalad-container.svg)](https://GitHub.com/datalad/datalad-container/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad_container.svg)](https://pypi.python.org/pypi/datalad_container/) | ![-](https://anaconda.org/conda-forge/datalad-container/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_container/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_container) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-container.png?branch=master)](https://travis-ci.org/datalad/datalad-container) | [![codecov.io](https://codecov.io/github/datalad/datalad-container/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-container?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-container.svg)](http://isitmaintained.com/project/datalad/datalad-container "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-container.svg)](http://isitmaintained.com/project/datalad/datalad-container "Percentage of issues still open") | 
 | [datalad_metalad](https://github.com/datalad/datalad-metalad) | [![?](https://img.shields.io/github/release/datalad/datalad-metalad.svg)](https://GitHub.com/datalad/datalad-metalad/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-metalad.svg)](https://pypi.python.org/pypi/datalad-metalad/) | ![-](https://anaconda.org/conda-forge/datalad-metalad/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_metalad/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_metalad) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-metalad.png?branch=master)](https://travis-ci.org/datalad/datalad-metalad) | [![codecov.io](https://codecov.io/github/datalad/datalad-metalad/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-metalad?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-metalad.svg)](http://isitmaintained.com/project/datalad/datalad-metalad "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-metalad.svg)](http://isitmaintained.com/project/datalad/datalad-metalad "Percentage of issues still open") | 
 | [datalad_crawler](https://github.com/datalad/datalad-crawler) | [![?](https://img.shields.io/github/release/datalad/datalad-crawler.svg)](https://GitHub.com/datalad/datalad-crawler/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad_crawler.svg)](https://pypi.python.org/pypi/datalad_crawler/) | ![-](https://anaconda.org/conda-forge/datalad-crawler/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_crawler/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_crawler) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-crawler.png?branch=master)](https://travis-ci.org/datalad/datalad-crawler) | [![codecov.io](https://codecov.io/github/datalad/datalad-crawler/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-crawler?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-crawler.svg)](http://isitmaintained.com/project/datalad/datalad-crawler "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-crawler.svg)](http://isitmaintained.com/project/datalad/datalad-crawler "Percentage of issues still open") | 
 | [datalad_webapp](https://github.com/datalad/datalad-webapp) | [![?](https://img.shields.io/github/release/datalad/datalad-webapp.svg)](https://GitHub.com/datalad/datalad-webapp/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-webapp.svg)](https://pypi.python.org/pypi/datalad-webapp/) | ![-](https://anaconda.org/conda-forge/datalad-webapp/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_webapp/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_webapp) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-webapp.png?branch=master)](https://travis-ci.org/datalad/datalad-webapp) | [![codecov.io](https://codecov.io/github/datalad/datalad-webapp/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-webapp?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-webapp.svg)](http://isitmaintained.com/project/datalad/datalad-webapp "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-webapp.svg)](http://isitmaintained.com/project/datalad/datalad-webapp "Percentage of issues still open") | 
 | [datalad_hirni](https://github.com/psychoinformatics-de/datalad-hirni) | [![?](https://img.shields.io/github/release/psychoinformatics-de/datalad-hirni.svg)](https://GitHub.com/psychoinformatics-de/datalad-hirni/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-hirni.svg)](https://pypi.python.org/pypi/datalad-hirni/) | ![-](https://anaconda.org/conda-forge/datalad-hirni/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_hirni/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_hirni) | [![master+Released Datalad](https://secure.travis-ci.org/psychoinformatics-de/datalad-hirni.png?branch=master)](https://travis-ci.org/psychoinformatics-de/datalad-hirni) | [![codecov.io](https://codecov.io/github/psychoinformatics-de/datalad-hirni/coverage.svg?branch=master)](https://codecov.io/github/psychoinformatics-de/datalad-hirni?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/psychoinformatics-de/datalad-hirni.svg)](http://isitmaintained.com/project/psychoinformatics-de/datalad-hirni "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/psychoinformatics-de/datalad-hirni.svg)](http://isitmaintained.com/project/psychoinformatics-de/datalad-hirni "Percentage of issues still open") | 
 | [datalad_ukbiobank](https://github.com/datalad/datalad-ukbiobank) | [![?](https://img.shields.io/github/release/datalad/datalad-ukbiobank.svg)](https://GitHub.com/datalad/datalad-ukbiobank/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad_ukbiobank.svg)](https://pypi.python.org/pypi/datalad_ukbiobank/) | ![-](https://anaconda.org/conda-forge/datalad-ukbiobank/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_ukbiobank/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_ukbiobank) | [![master+Released Datalad](https://secure.travis-ci.org/datalad/datalad-ukbiobank.png?branch=master)](https://travis-ci.org/datalad/datalad-ukbiobank) | [![codecov.io](https://codecov.io/github/datalad/datalad-ukbiobank/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-ukbiobank?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-ukbiobank.svg)](http://isitmaintained.com/project/datalad/datalad-ukbiobank "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-ukbiobank.svg)](http://isitmaintained.com/project/datalad/datalad-ukbiobank "Percentage of issues still open") | 
