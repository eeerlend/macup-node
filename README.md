# macup-node

A [macup](https://github.com/eeerlend/macup-builder) module that enables you to easily install global Node modules via NPM.

## Installation
Run the following command to add it to your repo

```bash
npm install eeerlend/macup-node
```

## Configuration
Add global Node packages via NPM. Node is installed via Homebrew if it's not already installed. Homebrew is installed if it's not already installed.

```bash
macup_node_packages+=(
  tree-cli
  browser-sync
  @vue/cli
)
```
