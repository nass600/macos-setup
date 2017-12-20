#  macOS setup

[![Build Status](https://travis-ci.org/nass600/macos-setup.svg?branch=master)](https://travis-ci.org/nass600/macos-setup)

One-click setup for a freshly installed macOS via Ansible

> Working in macOS 10.12 High Sierra

## Installation

1. First download your ssh key or create a new one by executing:

  ```bash
  ssh-keygen
  ```

2. Run the installation script:

  ```bash
  sh <(curl -L https://raw.github.com/nass600/macos-setup/master/bin/install)
  ```

Will install:

+ App Store applications
+ Brew packages
+ Brew Casks
+ Powerline and vundle (terminal)

## License

[MIT](LICENSE)

## Author

[Ignacio Velazquez](http://ignaciovelazquez.es)
