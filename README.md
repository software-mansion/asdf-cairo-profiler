<div align="center">

# asdf-cairo-profiler [![Build](https://github.com/software-mansion/asdf-cairo-profiler/actions/workflows/build.yml/badge.svg)](https://github.com/software-mansion/asdf-cairo-profiler/actions/workflows/build.yml) [![Lint](https://github.com/software-mansion/asdf-cairo-profiler/actions/workflows/lint.yml/badge.svg)](https://github.com/software-mansion/asdf-cairo-profiler/actions/workflows/lint.yml)

[cairo-profiler](https://github.com/software-mansion/cairo-profiler) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add cairo-profiler
# or
asdf plugin add cairo-profiler https://github.com/software-mansion/asdf-cairo-profiler.git
```

cairo-profiler:

```shell
# Show all installable versions
asdf list all cairo-profiler

# Install specific version
asdf install cairo-profiler latest

# Set a version globally (on your ~/.tool-versions file)
asdf set --home cairo-profiler latest

# Now cairo-profiler commands are available
cairo-profiler --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# License

See [LICENSE](LICENSE) © [Wojciech Szymczyk](https://github.com/software-mansion/)
