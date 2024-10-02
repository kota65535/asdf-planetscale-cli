<div align="center">

# asdf-planetscale-cli [![Build](https://github.com/kota65535/asdf-planetscale-cli/actions/workflows/build.yml/badge.svg)](https://github.com/kota65535/asdf-planetscale-cli/actions/workflows/build.yml) [![Lint](https://github.com/kota65535/asdf-planetscale-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/kota65535/asdf-planetscale-cli/actions/workflows/lint.yml)

[planetscale-cli](https://planetscale.com/docs/reference/planetscale-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add planetscale-cli
# or
asdf plugin add planetscale-cli https://github.com/kota65535/asdf-planetscale-cli.git
```

planetscale-cli:

```shell
# Show all installable versions
asdf list-all planetscale-cli

# Install specific version
asdf install planetscale-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global planetscale-cli latest

# Now planetscale-cli commands are available
pscale --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kota65535/asdf-planetscale-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tomohiko Ozawa](https://github.com/kota65535/)
