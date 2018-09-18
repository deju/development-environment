## bash env

### .bash_profile

    # copy the following into ~/.bash_profile (touch it if not exists)

    alias ll="ls -la"
    alias c="clear"
    export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
    export CLICOLOR=1
    export LSCOLORS=ExFxBxDxCxegedabagacad