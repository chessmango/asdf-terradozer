<div align="center">

# asdf-terradozer [![Build](https://github.com/chessmango/asdf-terradozer/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-terradozer/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-terradozer/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-terradozer/actions/workflows/lint.yml)


[terradozer](https://github.com/jckuester/terradozer) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add terradozer https://github.com/chessmango/asdf-terradozer.git
```

terradozer:

```shell
# Show all installable versions
asdf list-all terradozer

# Install specific version
asdf install terradozer latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terradozer latest

# Now terradozer commands are available
terradozer --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-terradozer/graphs/contributors)!

# License

See [LICENSE](LICENSE)
