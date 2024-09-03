# poetry-scripts
Installation/Uninstallation scripts of Python poetry virtualenv manager.

## Installation

By default, Poetry is installed into a platform and user-specific directory:

`~/Library/Application Support/pypoetry` on MacOS.
`~/.local/share/pypoetry` on Linux/Unix.
`%APPDATA%\pypoetry` on Windows.

### Basic
```shell
python3 install_poetry.py
```

### Specific Version
```shell
python3 install_poetry.py --version 1.2.0

# or
POETRY_VERSION=1.2.0 python3 install_poetry.py
```

### Pre-release Version
```shell
python3 install_poetry.py --preview

# or
POETRY_PREVIEW=1 python3 install_poetry.py
```

## Uninstallation

```shell
python3 ./install_poetry.py --uninstall
```