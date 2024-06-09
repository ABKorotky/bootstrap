# Bootstrap
The repo contains several useful skeletons for quick starting new Python projects


## Package skeleton
The skeleton provides the smallest configuration for Python packages.
It contains:
- `<bootstrap-dir>` directory. It's a python package. It contains package info and `tests` sub-directory.
- `docs` directory. It contains skeletons for generating procect documentation.
- `CHANGELOG.md` file with versioning info.
- `README.md` file with project description.
- `pyproject.toml` file with configuration for `black`, `isort`, `flake`, `mypy`, `coverage` and `tox` tools.
- `requirements.txt` file with list of Python dependencies.
- `requirements-dev.txt` file for automation dependencies.
- `.pre-commit-config.yaml` file with configuration for `pre-commit` tool.

### How to use
1. Copy-paste the directory.
2. Make global substitution the followings placeholders:
    - `<bootstrap-dir>`. **Required**. Directory name where your code is located.
    - `<bootstrap-python-minor>`. **Required**. It's a number. `12` for instance. Major version is `3`.
    - `<bootstrap-name>`. Package technical name.
    - `<bootstrap-title>`. Package human-readable name.
    - `<bootstrap-description>`. Package description.
    - `<bootstrap-author>`. Package autor first and last names.
    - `<bootstrap-author-email>`. Package autor email.
    - `<bootstrap-year>`. Current date in the following format: `YYYY-MM-DD`.
    - `<bootstrap-version-date>`. Current date in the following format: `YYYY-MM-DD`.
    - `<bootstrap-repo-git>`. A path to git repository for cloning.
    - `<bootstrap-repo-http>`. A path to git repository for cloning.

Required placeholders are important for automation.
Optional placeholders just provide some level of beauty.
