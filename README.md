#  macOS setup

> One-click setup for a freshly installed macOS via Ansible
> Working in macOS 13 Ventura

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
+ macOS preferences

## TODO

- [ ] Disable Mission control keyboard shortcuts
- [ ] Modify Spotlight sources
- [ ] Auto check Software Updates

## License

[MIT](LICENSE)

## Author

[Ignacio Velazquez](http://ignaciovelazquez.es)
