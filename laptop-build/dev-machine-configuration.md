# Toolkit Summary

- AWS CLI
- Python 3.x
- AWS Amplify
- Python Chalice Micro Framework
- Firecracker
- IDEs *

  ## Operating System

  These steps apply to Mac. Preference is to you use brew as the package manager for Mac

## Install the AWS CLI

- You can use PIP, Brew on Mac or grab the tarball
- run ` ``aws configure` to setup your aws user (need to generate access and secret access keys in your account)

## Install Python 3.x

Python 2.7 goes unsupported in 2020 so beat to upgrade it

- `brew install python` will install 3.x
- `pip install virtualenv`

## Install Atom

- `brew cask install atom`
- Install packages

  - tidy-markdown
  - atom-beautify

## Install git

- `brew install git`

## Install Useful \*nix Packages

- `brew install tree`

## Install AWS Amplify

- Install Node.js® and npm if they are not already on your machine `brew install node`
- `npm install -g @aws-amplify/cli`
- run `amplify configure` to setup your aws user (need to generate access and secret access keys in your account)
- `brew install yarn` for web expo amplify build
- then follow <https://aws-amplify.github.io/docs/js/start> to build a demo amplify app *

  ## Install Docker

  [https://medium.com/@yutafujii_59175/a-complete-one-by-one-guide-to-install-docker-on-your-mac-os-using-homebrew-e818eb4cfc3](mailto:https://medium.com/@yutafujii_59175/a-complete-one-by-one-guide-to-install-docker-on-your-mac-os-using-homebrew-e818eb4cfc3)

- `brew cask install docker`

- `brew install docker-machine`

- `brew cask install virtualbox`

## Install Python Chalice Micro framework

<https://chalice-workshop.readthedocs.io/en/latest/env-setup.html>

- Then follow <https://chalice-workshop.readthedocs.io/en/latest/todo-app/index.html> to build the demo app and CICD environment

## Install Firecracker

## Install an IDE

I install VSSCode and Eclipse for training demo purposes

- Install VSS Code

  - Install Git Lens package
  - Install Python tools

- Install Eclipse IDE for Java Developers
