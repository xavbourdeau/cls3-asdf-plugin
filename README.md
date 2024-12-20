<div align="center">

# asdf-cls3 [![Build](https://github.com/xavbourdeau/asdf-cls3/actions/workflows/build.yml/badge.svg)](https://github.com/xavbourdeau/asdf-cls3/actions/workflows/build.yml) [![Lint](https://github.com/xavbourdeau/asdf-cls3/actions/workflows/lint.yml/badge.svg)](https://github.com/xavbourdeau/asdf-cls3/actions/workflows/lint.yml)

[cls3](https://github.com/xavbourdeau/cls3-asdf-plugin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

No dependencies so far

# Install

Plugin:

```shell
asdf plugin add cls3
# or
asdf plugin add cls3 https://github.com/xavbourdeau/cls3-asdf-plugin.git
```

cls3:

```shell
# Show all installable versions
asdf list-all cls3

# Install specific version
asdf install cls3 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cls3 latest

# Now cls3 commands are available
cls3 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/xavbourdeau/asdf-cls3/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Xavier Bourdeau](https://github.com/xavbourdeau/)
