<div align="center">

# asdf-dua [![Build](https://github.com/xyb/asdf-dua/actions/workflows/build.yml/badge.svg)](https://github.com/xyb/asdf-dua/actions/workflows/build.yml) [![Lint](https://github.com/xyb/asdf-dua/actions/workflows/lint.yml/badge.svg)](https://github.com/xyb/asdf-dua/actions/workflows/lint.yml)

[dua](https://github.com/Byron/dua-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add dua
# or
asdf plugin add dua https://github.com/xyb/asdf-dua.git
```

dua:

```shell
# Show all installable versions
asdf list all dua

# Install specific version
asdf install dua latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u dua latest

# Now dua commands are available
dua --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/xyb/asdf-dua/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Xie Yanbo](https://github.com/xyb/)
