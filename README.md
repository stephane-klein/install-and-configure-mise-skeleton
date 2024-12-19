# MySuper development kit

...

## Workspace installation and configuration

### On OSX: install with Brew

Brew is a popular package manager on *macOS*.
However, it does not come pre-installed: follow the instructions from the Brew [Website](https://brew.sh/index_fr):

```sh
$ brew install git mise
```

Next, activate mise ([you can see official documentation](https://mise.jdx.dev/getting-started.html))

If you use **Bash** shell execute:

```sh
$ echo 'eval "$(mise activate bash)"' >> ~/.bashrc
$ source ~/.bash_profile
```

If you use **Zsh** shell execute:

```sh
$ echo 'eval "$(mise activate zsh)"' >> "${ZDOTDIR-$HOME}/.zshrc"
$ source ~/.zsrhrc
```

```
$ mise settings set experimental true
$ mise install -y
```

## Workspace usage

```sh
$ mise trust
```

```
$ echo $HELLO_WORLD
foo
```
