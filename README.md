<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-xresources/develop/src/assets/nord-xresources-banner.svg"/></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xresources/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-xresources.svg?style=flat-square&color=88C0D0&label=Release"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://wiki.archlinux.org/index.php/x_resources">Xresources</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xresources/develop/src/assets/scrot-colortest.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Getting started
### Installation
Detailed information about Xresources configurations can be found in the [Arch Linux Wiki](https://wiki.archlinux.org/index.php/X_resources) and [Wikipedia](https://en.wikipedia.org/wiki/X_resources).

#### Manual
Copy the content of the [`nord`](https://github.com/arcticicestudio/nord-xresources/blob/develop/src/nord) file into the `~/.Xresources` or `~/.Xdefaults` file and reload the settings with `xrdb`.

#### Via `#include`
Copy the [`nord`](https://github.com/arcticicestudio/nord-xresources/blob/develop/src/nord) file to any place and import it via `#include "/path/to/nord"`.

#### Via `merge`
To merge the color theme into your current settings copy the [`nord`](https://github.com/arcticicestudio/nord-xresources/blob/develop/src/nord) file to any place and run `xrdb -merge path/to/nord`.

## Screenshots
<p align="center"><strong>htop</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xresources/develop/src/assets/scrot-htop.png"/></p>

## Development
[![](https://img.shields.io/badge/Changelog-0.1.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-xresources/blob/v0.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-xresources/issues).

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/nord/repository-footer-separator.svg?sanitize=true" /></p>

<p align="center">Copyright &copy; 2016-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xresources/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>
