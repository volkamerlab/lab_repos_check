# Volkamer Lab's repositories check

This is an overview of our published repositories' status:
- CI status
- Documentation status
- Number of open issues
- Number of open PRs
- Code coverage (CodeCov)
- Conda version
- License

## Status

| Repository | CI | Docs | #Issues | #PRs | CodeCov | Conda | Licence |
|---|---|---|---|---|---|---|---|
| [teachopencadd](https://github.com/volkamerlab/teachopencadd) | [![GH Actions CI ](https://github.com/volkamerlab/teachopencadd/workflows/CI/badge.svg)](https://github.com/volkamerlab/teachopencadd/actions?query=branch%3Amaster+workflow%3ACI) | [![GH Actions Docs](https://github.com/volkamerlab/teachopencadd/workflows/Docs/badge.svg)](https://projects.volkamerlab.org/teachopencadd/) | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/teachopencadd) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/teachopencadd) | - | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/opencadd.svg)](https://anaconda.org/conda-forge/opencadd) | [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) |
| [opencadd](https://github.com/volkamerlab/opencadd) | [![GH Actions Status](https://github.com/volkamerlab/opencadd/workflows/CI/badge.svg)](https://github.com/volkamerlab/opencadd/actions?query=branch%3Amaster) | [![Documentation Status](https://readthedocs.org/projects/opencadd/badge/?version=latest)](https://opencadd.readthedocs.io) | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/opencadd) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/opencadd) | [![codecov](https://codecov.io/gh/volkamerlab/opencadd/branch/master/graph/badge.svg)](https://codecov.io/gh/volkamerlab/opencadd/branch/master) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/teachopencadd.svg)](https://anaconda.org/conda-forge/teachopencadd) | [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) |
| [kinfraglib](https://github.com/volkamerlab/kinfraglib) | [![GH Actions CI ](https://github.com/volkamerlab/kinfraglib/workflows/CI/badge.svg)](https://github.com/volkamerlab/kinfraglib/actions?query=branch%3Amaster+workflow%3ACI) | - | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/kinfraglib) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/kinfraglib) | - | - | [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) |
| [kissim](https://github.com/volkamerlab/kissim) | [![GH Actions CI ](https://github.com/volkamerlab/kissim/workflows/CI/badge.svg)](https://github.com/volkamerlab/kissim/actions?query=branch%3Amain+workflow%3ACI) | [![Documentation Status](https://readthedocs.org/projects/kissim/badge/?version=latest)](https://kissim.readthedocs.io) | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/kissim) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/kissim) | [![codecov](https://codecov.io/gh/volkamerlab/kissim/branch/main/graph/badge.svg)](https://codecov.io/gh/volkamerlab/kissim/branch/main) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/kissim.svg)](https://anaconda.org/conda-forge/kissim) | [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) |
| [kissim_app](https://github.com/volkamerlab/kissim_app) | [![GH Actions CI ](https://github.com/volkamerlab/kissim_app/workflows/CI/badge.svg)](https://github.com/volkamerlab/kissim_app/actions?query=branch%3Amaster+workflow%3ACI) | - | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/kissim_app) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/kissim_app) | - | - | [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) |
| [maxsmi](https://github.com/volkamerlab/maxsmi) | [![GH Actions CI ](https://github.com/volkamerlab/maxsmi/workflows/CI/badge.svg)](https://github.com/volkamerlab/maxsmi/actions?query=branch%3Amain+workflow%3ACI) | [![Documentation Status](https://readthedocs.org/projects/maxsmi/badge/?version=latest)](https://maxsmi.readthedocs.io) | ![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/maxsmi) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/maxsmi) | [![codecov](https://codecov.io/gh/volkamerlab/maxsmi/branch/main/graph/badge.svg)](https://codecov.io/gh/volkamerlab/maxsmi/branch/main) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/maxsmi.svg)](https://anaconda.org/conda-forge/maxsmi) | [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) |
| [website](https://github.com/volkamerlab/volkamerlab_org) | [![GH Actions CI ](https://github.com/volkamerlab/volkamerlab_org/workflows/CI/badge.svg)](https://github.com/volkamerlab/volkamerlab_org/actions?query=branch%3Amaster+workflow%3ACI) | - |![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/volkamerlab_org) | ![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/volkamerlab_org) | - | - | - |


## How to add a new repository

For a new repository `your_repo`,

1. Get CI badge as `[![GH Actions CI ](https://github.com/volkamerlab/your_repo/workflows/CI/badge.svg)](https://github.com/volkamerlab/your_repo/actions?query=branch%3Amain+workflow%3ACI)` (replace `main` with `master` if applicable to your repository).
2. Get Docs badge:
   - If docs are on ReadTheDocs: `[![Documentation Status](https://readthedocs.org/projects/your_repo/badge/?version=latest)](https://your_repo.readthedocs.io)`
   - If not but you have a separate Docs GHA workflow: `[![GH Actions Docs](https://github.com/volkamerlab/your_repo/workflows/Docs/badge.svg)](your-project-docs-url)`
3. Get #Issues badge as `![GitHub open issues](https://img.shields.io/github/issues/volkamerlab/your_repo)`.
4. Get #PRs badge as `![GitHub open pr](https://img.shields.io/github/issues-pr-raw/volkamerlab/your_repo)`.
5. Get CodeCov badge as `[![codecov](https://codecov.io/gh/volkamerlab/your_repo/branch/main/graph/badge.svg)](https://codecov.io/gh/volkamerlab/your_repo/branch/main)` (replace `main` with `master` if applicable to your repository).
6. Get Conda version badge as `[![Conda Version](https://img.shields.io/conda/vn/conda-forge/your_repo.svg)](https://anaconda.org/conda-forge/your_repo)`
7. Check the license on your GitHub repository and either copy-paste badges from this README (if license already represented) or visit https://shields.io/category/license to find your license.
