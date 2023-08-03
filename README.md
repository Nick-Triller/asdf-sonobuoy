<div align="center">

# asdf-sonobuoy [![Build](https://github.com/Nick-Triller/asdf-sonobuoy/actions/workflows/build.yml/badge.svg)](https://github.com/Nick-Triller/asdf-sonobuoy/actions/workflows/build.yml) [![Lint](https://github.com/Nick-Triller/asdf-sonobuoy/actions/workflows/lint.yml/badge.svg)](https://github.com/Nick-Triller/asdf-sonobuoy/actions/workflows/lint.yml)

[sonobuoy](https://sonobuoy.io/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `ASDF_SONOBUOY_OVERWRITE_ARCH`: override the CPU architecture (e.g. `x86_64`). Determined automatically with `uname -m` if unset.

# Install

Plugin:

```shell
asdf plugin add sonobuoy
# or
asdf plugin add sonobuoy https://github.com/Nick-Triller/asdf-sonobuoy.git
```

sonobuoy:

```shell
# Show all installable versions
asdf list-all sonobuoy

# Install specific version
asdf install sonobuoy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sonobuoy latest

# Now sonobuoy commands are available
sonobuoy help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Nick-Triller/asdf-sonobuoy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Triller](https://github.com/Nick-Triller/)
