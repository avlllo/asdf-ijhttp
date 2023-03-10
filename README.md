<div align="center">

# asdf-ijhttp [![Build](https://github.com/avlllo/asdf-ijhttp/actions/workflows/build.yml/badge.svg)](https://github.com/avlllo/asdf-ijhttp/actions/workflows/build.yml) [![Lint](https://github.com/avlllo/asdf-ijhttp/actions/workflows/lint.yml/badge.svg)](https://github.com/avlllo/asdf-ijhttp/actions/workflows/lint.yml)


[ijhttp](https://blog.jetbrains.com/idea/2022/12/http-client-cli-run-requests-and-tests-on-ci/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.
- `openjdk@17` is required by the tool

# Install

Plugin:

```shell
asdf plugin add ijhttp https://github.com/avlllo/asdf-ijhttp.git
```

ijhttp:

**Currently only `latest` version is supported**
```shell
# Show all installable versions
asdf list-all ijhttp

# Install specific version
asdf install ijhttp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ijhttp latest

# Now ijhttp commands are available
ijhttp --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/avlllo/asdf-ijhttp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [avlllo](https://github.com/avlllo/)
