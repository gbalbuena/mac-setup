# jenv

jenv is for a equivalent of rbenv, but for Java environment. It allow to easily switch between several JDKs installations (already presents), and configure which one to use per project.

For full documentation, see: https://github.com/hikage/jenv#readme

Install using brew:

```
brew update
brew cask install java
brew install jenv
```

Include this config in your bash profile

```
eval "$(jenv init -)"
```