<div align="center">

# asdf-goldwarden [![Build](https://github.com/vhdirk/asdf-goldwarden/actions/workflows/build.yml/badge.svg)](https://github.com/vhdirk/asdf-goldwarden/actions/workflows/build.yml) [![Lint](https://github.com/vhdirk/asdf-goldwarden/actions/workflows/lint.yml/badge.svg)](https://github.com/vhdirk/asdf-goldwarden/actions/workflows/lint.yml)

[goldwarden](https://github.com/quexten/goldwarden) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add goldwarden
# or
asdf plugin add goldwarden https://github.com/vhdirk/asdf-goldwarden.git
```

goldwarden:

```shell
# Show all installable versions
asdf list-all goldwarden

# Install specific version
asdf install goldwarden latest

# Set a version globally (on your ~/.tool-versions file)
asdf global goldwarden latest

# Now goldwarden commands are available
goldwarden --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vhdirk/asdf-goldwarden/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dirk Van Haerenborgh](https://github.com/vhdirk/)
