# Dotfiles

Version control entry of my dotfiles.

## How to use

### Prepare dpendency

Install brew first

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install packages

```sh
brew install git vcsh
```

### Bootstrapping

```sh
vcsh clone -b main https://github.com/longwdl/vcsh-mr.git mr
mr update
```

# LICENSE

This project is licensed under the terms of the [MIT LICENSE](http://opensource.org/licenses/MIT)

