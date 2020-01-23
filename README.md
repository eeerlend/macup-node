# macup-node

A [macup](https://github.com/eeerlend/macup-builder) module that keeps your dotfiles in sync through cloud drive

## Installation
Run the following command to add it to your repo

```bash
npm install eeerlend/macup-node
```

## Configuration
Add your dotfiles to your macup configuration file like this...

```bash
macup_node_packages+=(
  tree-cli
  browser-sync
  @vue/cli
)
```
