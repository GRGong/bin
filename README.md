### my ~bin

with following zshrc/bashrc
```

if [ -x /usr/bin/dircolors ]; then
    test -r ~/.dircolors && eval "$(dircolors -b ~/.dircolors)" || eval "$(dircolors -b)"
    alias ls='ls --color=auto'
    #alias dir='dir --color=auto'
    #alias vdir='vdir --color=auto'

    alias grep='grep --color=auto'
    alias fgrep='fgrep --color=auto'
    alias egrep='egrep --color=auto'
fi


alias ll='ls -l --color=auto'
alias ls='ls --color=auto'
alias rp='realpath'
alias vim='nvim'
alias l='exa -l'



#for zsh-only
setopt noautomenu
setopt nomenucomplete

```
