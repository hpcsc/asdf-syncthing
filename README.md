# asdf-syncthing

This is a plugin for [asdf](https://github.com/asdf-vm/asdf) to install/manage [syncthing](https://github.com/syncthing/syncthing)

## Installation

```
asdf plugin-add syncthing https://github.com/hpcsc/asdf-syncthing.git
```

## Usage

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for general usage of asdf.

Most common usage:

```
asdf list-all syncthing # to list available versions of syncthing installation files
asdf install syncthing [latest|x.y.z] # to get latest|x.y.z version of syncthing installation files
asdf global syncthing x.y.z # set version x.y.z as global
```
