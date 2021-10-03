<div align="center">

# asdf-vercel-cli [![Build](https://github.com/sotalbireo/asdf-vercel-cli/actions/workflows/build.yml/badge.svg)](https://github.com/sotalbireo/asdf-vercel-cli/actions/workflows/build.yml) [![Lint](https://github.com/sotalbireo/asdf-vercel-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/sotalbireo/asdf-vercel-cli/actions/workflows/lint.yml)


[vercel-cli](https://github.com/vercel/vercel/tree/main/packages/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add vercel-cli
# or
asdf plugin add vercel-cli https://github.com/sotalbireo/asdf-vercel-cli.git
```

vercel-cli:

```shell
# Show all installable versions
asdf list-all vercel-cli

# Install specific version
asdf install vercel-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vercel-cli latest

# Now vercel-cli commands are available
vercel --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sotalbireo/asdf-vercel-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [sasaky](https://github.com/sotalbireo/)
