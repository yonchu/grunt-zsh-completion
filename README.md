# grunt-zsh-completion

`grunt-zsh-completion` is the zsh completion script for
[grunt](https://github.com/gruntjs/grunt)/
[grunt-cli](https://github.com/gruntjs/grunt-cli)


![Screenshot1](https://raw.github.com/yonchu/grunt-zsh-completion/master/img/screenshot01.png)

![Screenshot2](https://raw.github.com/yonchu/grunt-zsh-completion/master/img/screenshot02.png)


## Installation

Put the `_grunt` file to the `fpath` directory.

```sh
$ cp _grunt /usr/local/share/zsh/site-functions/
$ exec zsh
```

Where the `fpath` directory is ?

```sh
$ echo "$fpath" | tr " " "\n"
```
