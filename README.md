# Dotfiles and Configurations - Tmux

## Introduction
### Background
```
This repository contains the Tmux configuration I use on all my systems that is running Tmux
```

### System
- version tested
    + 2023-08-16 1604H : 3.1c

### Packages/Plugins
+ Please refer to [plugins](plugins.md) for the full list of plugins/packages used (WIP)

### Neovim
- Tmux is a Terminal Multiplexer, where "session servers" are created in the background, having shells running in the background as seperate processes 
    - A terminal multiplexer allows a user to have multiple shell sessions happening at the same instance, 
        - and even if the terminal emulator is closed, the shell instance is still running in the background, 
            + allowing you to re-attach and re-enter back into the instance.
- Alternatives includes
    + 'screen' Terminal Multiplexer
- Project Structure
    + Configuration folder: ~/
    + Configuration file: .tmux.conf

## Setup
### Dependencies
+ tmux
+ git    : For installing/pulling packages

### Pre-Requisites
- Place the config folder into your ~/.config/tmux/ folder
    ```console
    cp -r src/tmux ~/.config/tmux
    ```
- Place the config file into your home folder
    ```console
    cp src/.tmux.conf ~/.tmux.conf
    ```

### Post-Installation
- To install the plugins
    + Type '[Prefix] + i' on the first startup

## Documentations
### Contents
+ README.md : This README
+ plugins.md : The full list of plugins
+ src/ : Contains the configurations

## Wiki

## Resources

## References

## Remarks
