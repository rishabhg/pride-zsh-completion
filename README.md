#pride-zsh-completion

*`pride-zsh-completion` is the zsh completion script for
[Pride](https://github.com/prezi/pride)*

## Installation

Put the `_pride` file to the `fpath` directory.

```sh
$ cp _pride /usr/local/share/zsh/site-functions/
$ exec zsh
```

Where the `fpath` directory is ?

```sh
$ echo "$fpath" | tr " " "\n"
```

## Installation for oh-my-zsh

1. In the command line, change to `oh-my-zsh` plugins directory:

    ```console
    $ cd ~/.oh-my-zsh/custom/plugins
    ```

2. Clone the repository into a new directory called `pride`:

    ```console
    git clone git@github.com:rishabhg/pride-zsh-completion.git pride
    ```

3. Include `pride` plugin to your .zshrc file along with other plugins:

    ```zsh
    ...
    plugins=(git pride)
    ...
    ```

4. Reload your shell:

    ```console
    $ exec zsh
    ```
## Usage

Currently all commonly used `pride` commands are supported

```console
$ pride <tab>
  config  --  Set configuration parameters
  do      --  Execute a command on a set of the modules
  help    --  Display help information
  init    --  Initialize pride
  list    --  Lists modules in a pride
  remove  --  Remove modules from a pride
  update  --  Updates a pride
  vesion  --  Display pride version
```


## Requirements

- [Pride](https://github.com/prezi/pride)
- [zsh](http://www.zsh.org/)
- Optional: [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

