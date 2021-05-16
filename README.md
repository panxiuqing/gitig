# Gitig

Simple command line tool to init gitignore file.

## Usage

Download executable target file from Releases and put it to your $PATH, then:

```sh
# Create .gitignore file for Python project to current position
gitig init Python
```

## .gitignore remote set

The default template set is fetched from [github/gitignore](https://github.com/github/gitignore) repo.

You can change it by add a config file `$HOME/.gitig.yml` with contents:

```yml
# Make sure a gitignore file can be fetched through http/https and end with Language.gitignore
# e.g. https://you.own.template.set/Python.gitignore
remote_set: https://you.own.template.set/
```
