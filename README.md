#  macOS setup

[![api](<https://img.shields.io/badge/macos_15_(sequoia)-white?style=for-the-badge&logo=apple&logoColor=black>)]()
[![GitHub tag](https://img.shields.io/github/tag/nass600/macos-setup.svg?style=for-the-badge&logo=github)]()

One-click setup for a freshly installed macOS via Ansible

> Working in **macOS 15 Sequoia**

## Installation

1. Make sure you can pull code from GitHub having your ssh keys in the `~/.ssh/` directory.

2. Run the installation script:

   ```bash
   sh <(curl -L https://raw.github.com/nass600/macos-setup/main/bin/install)
   ```

The script will install:

- App Store applications
- Homebrew packages and casks
- Zsh Antigen plugins and Powerline10k
- Vim Vundle
- macOS preferences

For an in-depth detail, you can check the [`default.config.yml`](default.config.yml)

## Uninstallation

Running the following script will remove all the **default** artifacts generated by the installation script:

```bash
sh .macos-setup/bin/uninstall
```

## License

[MIT](LICENSE)

## Author

[Ignacio Velazquez](http://ignaciovelazquez.es)
