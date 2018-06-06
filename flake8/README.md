This will set up PyCharm use flake8 for linting, so you can take advantage of plugins and settings that the pycharm editor dosnt support (in my case, trailing commas)

## Installation

1. Install `flake8` and plugins with `pip install flake8 flake8-commas flake8-comprehensions flake8-per-file-ignores`
2. Go to 'Preferences' > 'Tools' > 'File Watchers'
3. Click on the 'import' button (the one with the green arrow) and select the `flake8.xml` file from this directory

A sample `tox.ini` file for django projects is included in this directory for convenience.
