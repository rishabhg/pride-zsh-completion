pride-zsh-completion
===============
*Z shell autocomplete plugin for [Pride](https://github.com/prezi/pride)*

Status
------


Usage
-----

#### oh-my-zsh

* Create a new folder `pride` in oh-my-zsh custom plugin directory:

        $ mkdir ~/.oh-my-zsh/custom/plugins/pride/

* Clone the contents of repo in this directory:

        $ cd ~/.oh-my-zsh/custom/plugins/pride/
        $ git clone git@github.com:rishabhg/pride-zsh-completion.git .

* Reload your shell:

        $ exec $SHELL
        
Support
-------
Currently all commonly used `pride` commands are supported

```
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

License
-------
