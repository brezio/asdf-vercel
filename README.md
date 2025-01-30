<div align="center">

# asdf-vercel [![Build](https://github.com/brezio/asdf-vercel/actions/workflows/build.yml/badge.svg)](https://github.com/brezio/asdf-vercel/actions/workflows/build.yml) [![Lint](https://github.com/brezio/asdf-vercel/actions/workflows/lint.yml/badge.svg)](https://github.com/brezio/asdf-vercel/actions/workflows/lint.yml)

[vercel](https://github.com/brezio/asdf-vercel) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add vercel
# or
asdf plugin add vercel https://github.com/brezio/asdf-vercel.git
```

vercel:

```shell
# Show all installable versions
asdf list-all vercel

# Install specific version
asdf install vercel latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vercel latest

# Now vercel commands are available
vercel --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/brezio/asdf-vercel/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bob Breznak](https://github.com/brezio/)
