<div align="center">

# asdf-cairo-profiler [![Build](https://github.com/THenry14/asdf-cairo-profiler/actions/workflows/build.yml/badge.svg)](https://github.com/THenry14/asdf-cairo-profiler/actions/workflows/build.yml) [![Lint](https://github.com/THenry14/asdf-cairo-profiler/actions/workflows/lint.yml/badge.svg)](https://github.com/THenry14/asdf-cairo-profiler/actions/workflows/lint.yml)

[cairo-profiler](https://github.com/software-mansion/cairo-profiler) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cairo-profiler
# or
asdf plugin add cairo-profiler https://github.com/THenry14/asdf-cairo-profiler.git
```

cairo-profiler:

```shell
# Show all installable versions
asdf list-all cairo-profiler

# Install specific version
asdf install cairo-profiler latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cairo-profiler latest

# Now cairo-profiler commands are available
cairo-profiler --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/THenry14/asdf-cairo-profiler/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Wojciech Szymczyk](https://github.com/THenry14/)
