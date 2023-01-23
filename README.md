<div align="center">

# asdf-serverless [![Build](https://github.com/pdemagny/asdf-serverless/actions/workflows/build.yml/badge.svg)](https://github.com/pdemagny/asdf-serverless/actions/workflows/build.yml) [![Lint](https://github.com/pdemagny/asdf-serverless/actions/workflows/lint.yml/badge.svg)](https://github.com/pdemagny/asdf-serverless/actions/workflows/lint.yml)


[serverless](https://www.serverless.com/framework/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add serverless
# or
asdf plugin add serverless https://github.com/pdemagny/asdf-serverless.git
```

serverless:

```shell
# Show all installable versions
asdf list-all serverless

# Install specific version
asdf install serverless latest

# Set a version globally (on your ~/.tool-versions file)
asdf global serverless latest

# Now serverless commands are available
serverless --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pdemagny/asdf-serverless/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre Demagny](https://github.com/pdemagny/)
