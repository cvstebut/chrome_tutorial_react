# chrome_tutorial_react
Chrome Extension - Following along with https://github.com/manshu/reactjs-chrome-extension and accompanying youtube series

## Links

- [Github - manshu - react-chrome-extension](https://github.com/manshu/reactjs-chrome-extension)
- [batra.dev - Videos](https://www.batra.dev/videos)
- [batra.dev - React Chrome Extension](https://www.batra.dev/videos/reactjs-chrome-extension)
- [YouTube - gurulabsdev / manshu - Playlist React Chrome Extension](https://www.youtube.com/watch?v=rAZXWkVhCgg&list=PLBS1L3Ug2VVods9GnWbJc__STt9VnrJ9Z)

## Dev Environment

Using Windows WSL 2: ulab01

### fnm, node, npm

- cross platform (Linux, Mac, Windows)
- Rust
- 11.1k Stars
- [GitHub - fnm](https://github.com/Schniz/fnm)
- [fnm doc](https://www.freecodecamp.org/news/fnm-fast-node-manager/)

```shell
curl -fsSL https://fnm.vercel.app/install | bash

export PATH="/home/ansible/.local/share/fnm:$PATH"
eval "`fnm env`"
source /home/ansible/.bashrc
```

```shell
fnm -V
fnm 1.33.1
```

```shell
ansible@ulab01:~$ fnm ls-remote
v0.1.14
v0.1.15
...
v19.5.0
v19.6.0
v19.6.1
v19.7.0
v19.8.0
v19.8.1
ansible@ulab01:~$ fnm current
none
ansible@ulab01:~$ fnm install 19
Installing Node v19.8.1 (x64)
ansible@ulab01:~$ fnm current
v19.8.1
```

update npm (minor version)
```shell
sudo npm install -g npm@9.6.2
```

### yarn

- [yarn - installation](https://classic.yarnpkg.com/en/docs/install#windows-stable)
- [yarn - migrate to current version (berry)](https://yarnpkg.com/getting-started/migration#why-should-you-migrate)

```shell
sudo npm install -g yarn
```

Upgrade to v2

```shell
ansible@ulab01:~$ yarn --version
1.22.19
ansible@ulab01:~$ yarn set version berry
warning package.json: No license field
➤ YN0000: Retrieving https://repo.yarnpkg.com/3.5.0/packages/yarnpkg-cli/bin/yarn.js
➤ YN0000: Saving the new release in .yarn/releases/yarn-3.5.0.cjs
➤ YN0000: Done in 0s 427ms
ansible@ulab01:~$ yarn --version
3.5.0
```

## Install Chrome Extension Locally

## Access Content of Web Page

## Parse Web Page and Retrieve Data

## Store Parsed Data on File System

## Store Parsed Data in Database