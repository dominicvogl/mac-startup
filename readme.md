# Install a brand new mac

inspired by: [Guide from Tania Rasica](https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/)

## Homebrew
### Install Homebrew

* [Find Homebrew Formulars](https://formulae.brew.sh/cask/)

Install Applications via Script

```. brew.sh```

These Applications I install via Mac App Store or Browser

* [JPEGMini](https://www.jpegmini.com/)
* [JPEGMini](https://www.jpegmini.com/)

### Install [Oh my Zsh](https://ohmyz.sh/) for Terminal

```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

## [Node.js]()

Use NVM to install npm and node

```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash```

Install Node
Install the latest version.

```nvm install node```

Restart terminal and run the final command.

```nvm use node```

Confirm that you are using the latest version of Node and npm.
```
node -v
npm -v
```

### Update

```nvm install node --reinstall-packages-from=node```
