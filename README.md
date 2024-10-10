# Python Project Template
The is python project template with basic configurations.

How to use on LINUX/MAC:

- Clone the repository;
- Copy all files and directory to you project, exclude README.MD;
- Make changes in 'pyproject.toml' file in [tool.poetry] based on you project;

Repeat follow commands in you project.
- Install Virtual Environment (venv):
```sh
python -m venv venv
```

- Activate venv:
```sh
source venv/bin/activate
```

- Install poetry
```sh
pip install poetry
```

- Install dependencies via poetry
```sh
poetry install
```

- Install pre-commit hooks
```sh
pre-commit install
```


The structure of a Python project can vary depending on the size and complexity of the project, but here are the general recommendations for organizing a standard Python project:

1. **`src/`** - This is the root directory for all source files of the project. All Python code should be located in this folder.

2. **`tests/`** - Folder for storing tests. These could be unit tests, integration tests, etc.

3. **`docs/`** - Folder for project documentation. Here you can store Markdown files or use tools like Sphinx to create documentation.

4. **`build/`** or **`dist/`** - Folder for storing project builds, such as wheel files or other artifacts.

5. **`venv/`** or **`env/`** - Folder for the Python virtual environment. This is where all project dependencies will be stored.

6. **`scripts/`** - Folder for scripts that can be used to manage the project, such as scripts for starting servers, automating tasks, etc.

7. **`data/`** - Folder for storing data that may be used in the project, such as databases, images, configuration files, etc.

8. **`config/`** - Folder for configuration files.

9. **`README.md`** - Description of the project, how to install, how to use, etc.

10. **`pyproject.toml`** - Project build configuration file, which you mentioned.

11. **`.gitignore`** - File to exclude files/folders from version control.

12. **`.pre-commit-config.yaml`** - File with configuration for pre-commit hooks.

These are the main components that can be in the structure of a Python project. Depending on the specifics of the project, some of these items may be absent or others may be added.