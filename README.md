# `zsh-plugin-speedtest`

A ZSH Plugin for completion for the `speedtest-cli`.

## Usage

Simply press tab or your auto-completion hotkey after typing in `speedtest-cli`:

```sh
speedtest-cli <TAB>
```

## Installation

Here are a few ways to install the plugin on different plugin managers:

### Manual

Run the following:

```sh
cd $HOME
git clone https://github.com/Yash-Singh1/zsh-plugin-speedtest.git
```

Then add the following code before you run `compinit` in your `.zshrc`:

```sh
export fpath=($HOME/zsh-plugin-speedtest $fpath)
```

### Antigen

Add the following in your `.zshrc`:

```sh
antigen bundle Yash-Singh1/zsh-plugin-speedtest
```

### Oh-my-zsh

1. Clone this repository in oh-my-zsh's `custom/plugins` directory:

    ```sh
    git clone https://github.com/Yash-Singh1/zsh-plugin-speedtest.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-plugin-speedtest
    ```

2. Activate the plugin in `~/.zshrc`:

    ```sh
    plugins=( [plugins...] zsh-plugin-speedtest)
    ```

3. Restart `zsh` (such as by opening a new instance of your terminal emulator).

### zgen

Add `zgen load Yash-Singh1/zsh-plugin-speedtest` to your `.zshrc`.

### zplug

Add `zplug "Yash-Singh1/zsh-plugin-speedtest", defer:2` to your `.zshrc`.
