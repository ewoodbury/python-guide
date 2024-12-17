# python-guide
Reference my Python setup

## pyenv
Seamless python version management
```bash
brew install pyenv

# Install new python version
pyenv install 3.10.14

# Check installed python versions
pyenv versions

# Set it as default global version
pyenv global 3.10.14

# Set it as the version to use from loca dir
pyenv local 3.10.14

# Choose python for only this shell session
pyenv shell 3.10.14
```

### pyenv-virtualenv
Virtual envs with pyenv
```bash
brew install pyenv-virtualenv

# Create new virtual env with specific python version
pyenv virtualenv 3.10.14 my-env

# Activate, deactivate, uninstall
pyenv activate my-env
pyenv deactivate
pyenv uninstall my-env
```
