# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test goldwarden https://github.com/vhdirk/asdf-goldwarden.git "goldwarden --help"
```

Tests are automatically run in GitHub Actions on push and PR.
