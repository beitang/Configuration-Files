File Usages
1. gitconfig: change file name to .gitconfig, put it to ~ directory, this is for --global configuration.


Other useful tips
1. git-completion
To get the script: curl https://raw.github.com/git/git/master/contrib/completion/git-completion.bash -o ~/.git-completion.bash
To add the script to ~/.bash_profile
if [ -f ~/.git-completion.bash ]; then
   . ~/.git-completion.bash
fi

