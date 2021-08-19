[![License](https://img.shields.io/github/license/sukkaw/zsh-proxy.svg?style=flat-square)](./LICENSE)

# Packer plugin

An [`oh-my-zsh`](https://ohmyz.sh/) plugin that adds some useful aliases/autocomplete features for [Packer](https://www.packer.io/).


## Installation

### oh-my-zsh

Firstly, clone this repository in `oh-my-zsh`'s plugins directory.

``zsh
git clone https://github.com/breakingpitt/zsh-packer.git ~/.oh-my-zsh/plugins/zsh-packer
```

Secondly, activate the plugin in `~/.zshrc`. Enable it by adding `zsh-packer` to the [plugins array](https://github.com/robbyrussell/oh-my-zsh/blob/master/templates/zshrc.zsh-template#L66).

```zsh
 plugins=(... packer)
```

## Aliases

- `pkr`: Runs the packer app.
- `pkr-bld`: Build image(s) from template.
- `pkr-con`: Creates a console for testing variable interpolation.
- `pkr-fix`: Fixes templates from old versions of packer.
- `pkr-fmt`: Rewrites HCL2 config files to canonical format.
- `pkr-upg`: Transform a JSON template into an HCL2 configuration.
- `pkr-init`: Install missing plugins or upgrade plugins.
- `pkr-ins`: Shows the components of a template.
- `pkr-val`: Check that the syntax and configuration of a template is valid.
- `pkr-ver`: Prints the Packer version, and checks for new release.


## Requirements

-  `Packer` 

## License

MIT License

Copyright (c) 2021 Pedro Garcia Rodriguez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Authors

- Pedro Garcia Rodriguez - [@BreakingPitt](http://www.breakingpitt.es)
