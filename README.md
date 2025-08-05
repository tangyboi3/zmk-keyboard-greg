# ZMK Module Template

This repository contains a module for greg :3

## Usage

[Put greg in your west.yml](https://zmk.dev/docs/features/modules#building-with-modules) under your zmk-config/config, e.g.:
```
manifest:
  remotes:
    - name: zmkfirmware
      url-base: https://github.com/zmkfirmware
    - name: tangyboi3
      url-base: https://github.com/tangyboi3
  projects:
    - name: zmk
      remote: zmkfirmware
      revision: main
      import: app/west.yml
    - name: zmk-keyboard-greg
      remote: tangyboi3
      revision: main
  self:
    path: config
```
Then you can treat greg [like any other keyboard](https://zmk.dev/docs/customization). Don't forget to configure greg's keymap, I left it blank intentionally.
