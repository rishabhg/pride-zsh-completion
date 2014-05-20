#pride-zsh-completion

*`pride-zsh-completion` is the zsh completion script for
[Pride](https://github.com/prezi/pride)*

##Setup

All you need is to add the `_pride` source to your `fpath` directory and call zsh commands for enabling auto-completion. The easy ways to do this are - 

### Installation

1. Clone the repository:

    ```console
    git clone git@github.com:rishabhg/pride-zsh-completion.git .
    ```

2. Install from make file:

    ```console
    $ sudo make install
    ```
3. Reload your shell:

    ```console
    $ exec zsh
    ```
    
### Installation for oh-my-zsh

1. In the command line, change to `oh-my-zsh` plugins directory:

    ```console
    $ cd ~/.oh-my-zsh/custom/plugins
    ```

2. Clone the repository into a new directory called `pride`:

    ```console
    $ git clone git@github.com:rishabhg/pride-zsh-completion.git pride
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


##Requirements

- [Pride](https://github.com/prezi/pride)
- [zsh](http://www.zsh.org/)
- Optional: [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
