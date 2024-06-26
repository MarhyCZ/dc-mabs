## Running

### Google Collab

Easiest method. This button launches notebook from this GitHub
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marhycz/dc-mabs/blob/main/bandits.ipynb)

### VS Code Dev Container

There is a predefined devcontainer.json with Python 3.11 and Jupyter extensions. So VS Code should detect it and offer you automatic installation of dev containers

### Pyenv

Using pyenv, you can install Python 3.11 version and then subsequent dependencies in Jupyter notebook.

```bash
pyenv install 3.11
```

After pyenv 3.11 installation, any python command should be automatically routed to 3.11 in this directory/repo if the pyenv is active using `.python-version` file
