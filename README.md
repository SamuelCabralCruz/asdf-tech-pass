<div align="center">

# asdf-tech-pass [![Build](https://github.com/SamuelCabralCruz/asdf-tech-pass/actions/workflows/build.yml/badge.svg)](https://github.com/SamuelCabralCruz/asdf-tech-pass/actions/workflows/build.yml) [![Lint](https://github.com/SamuelCabralCruz/asdf-tech-pass/actions/workflows/lint.yml/badge.svg)](https://github.com/SamuelCabralCruz/asdf-tech-pass/actions/workflows/lint.yml)

[tech-pass](https://git.tmaws.io/core-platform/tech-pass) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tech-pass
# or
asdf plugin add tech-pass https://github.com/SamuelCabralCruz/asdf-tech-pass.git
```

tech-pass:

```shell
# Show all installable versions
asdf list-all tech-pass

# Install specific version
asdf install tech-pass latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tech-pass latest

# Now tech-pass commands are available
tech-pass version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/SamuelCabralCruz/asdf-tech-pass/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Samuel Cabral Cruz](https://github.com/SamuelCabralCruz/)
