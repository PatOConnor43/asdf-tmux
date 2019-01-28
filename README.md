# asdf-tmux
tmux plugin for [asdf version manager](https://github.com/asdf-vm/asdf)


## Dependencies
- `git`
- `libevent` (apt-get install libevent-dev)
- `ncurses`
- Refer to the [tmux](https://github.com/tmux/tmux) README for more dependencies


## Install

```
asdf plugin-add tmux https://github.com/patoconnor43/asdf-tmux.git
```

## Use

This plugin supports `version` and `ref` install types. Meaning, you can install specific tagged versions are well as
specific commits. You can use any identifier that git uses for the commit that you want. As an example, if you wanted latest master, you would just use `asdf install tmux ref:master`. Remember, that this will install what is current master and will not automatically rebuild itself.


Check the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of tmux.

## Contributing

Feel free to create an issue or pull request if you find a bug.

## License
MIT License
