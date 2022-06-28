# luaenv-update

This [luaenv][] plugin adds the `luaenv update` command that updates [luaenv][] and all installed plugins.

Mostly copied from [rbenv-update][]

## Installation

Simply clone the repository into the plugins directory:

```sh
mkdir -p "$(luaenv root)/plugins"
git clone https://github.com/Sharparam/luaenv-update.git "$(luaenv root)/plugins/luaenv-update"
```

## License

Copyright &copy; 2022 by [Adam Hellberg][sharparam].

luaenv-update is licensed under the MIT License.
See the file `LICENSE` for more information.

[sharparam]: https://github.com/Sharparam
[luaenv]: https://github.com/cehoffman/luaenv
[rbenv-update]: https://github.com/rkh/rbenv-update
