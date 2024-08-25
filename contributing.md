# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test zephyr-rtos-sdk https://github.com/jadejr/asdf-zephyr-rtos-sdk.git "zephyr-rtos-sdk --help"
```

Tests are automatically run in GitHub Actions on push and PR.
