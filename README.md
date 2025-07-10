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

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

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
asdf list-all dua

# Install specific version
asdf install dua latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dua latest

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
