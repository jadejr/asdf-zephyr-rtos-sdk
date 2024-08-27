<div align="center">

# asdf-zephyr-rtos-sdk [![Build](https://github.com/jadejr/asdf-zephyr-rtos-sdk/actions/workflows/build.yml/badge.svg)](https://github.com/jadejr/asdf-zephyr-rtos-sdk/actions/workflows/build.yml) [![Lint](https://github.com/jadejr/asdf-zephyr-rtos-sdk/actions/workflows/lint.yml/badge.svg)](https://github.com/jadejr/asdf-zephyr-rtos-sdk/actions/workflows/lint.yml)

[zephyr-rtos-sdk](https://github.com/jadejr/zephyr-rtos-sdk) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `xz-utils` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `7za` on windows

# Install

Plugin:

```shell
asdf plugin add zephyr-rtos-sdk
# or
asdf plugin add zephyr-rtos-sdk https://github.com/jadejr/asdf-zephyr-rtos-sdk.git
```

zephyr-rtos-sdk:

```shell
# Show all installable versions
asdf list-all zephyr-rtos-sdk

# Install specific version
asdf install zephyr-rtos-sdk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zephyr-rtos-sdk latest

# Now zephyr-rtos-sdk commands are available
zephyr-rtos-sdk --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jadejr/asdf-zephyr-rtos-sdk/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Johnny Robeson](https://github.com/jadejr/)
