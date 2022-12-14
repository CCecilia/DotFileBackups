#!/usr/bin/env zsh

# Clipboard
alias cb=clipboard
alias cb-copy="xclip -sel clip"
alias cb-paste="xclip -selection clipboard -o"

# Machine Stuff
alias distro-ver="lsb_release -a"
alias goodnight="systemctl suspend"
alias update-snap-store="sudo pkill snap-store && sudo snap refresh snap-store"

# Shell
alias cc="clear"
alias ls="exa -laF --icons --group-directories-first --time-style iso"
alias dog="batcat"

# Work
alias start-cast-dev-server="npx webpack-dev-server --host $(subnetEth) --mode=development --env proxyHost='' --env proxyPort='' --env ldKey=$LD_KEY_QA --env sentryDsn=$SENTRY_DSN_QA"
alias deploy-to-qa="git push --delete origin deploy_to_qa && git tag deploy_to_qa-$(date +%+s) -f && git push -u origin --tags"
alias start-work="code $WORK_DIR/chromecast/"

# ZSH
alias zsh-up="source $HOME/.zshrc && printf \" \n ZSH updated \n \" " 
alias zsh-config="vim $HOME/.zshrc"

# Tmux
alias tmu-config="vim $HOME/.tmux.conf"
alias tmux-update="tmux source-file $HOME/.tmux.conf && printf \" \n TMUX Updated \n \" "

# Vim 
alias vim-config="vim $HOME/.vimrc"

# SSH
alias my-pi="ssh -X $PI_USERNAME@$PI_IP"
alias my-pi-wan="ssh $PI_USERNAME@$PI_IP -p $PI_PORT"
alias mb-pro="ssh $MAC_UNAME@$MAC_IP"

# Python
alias c-venv="python3 -m venv ./venv && source ./venv/bin/activate"

# Media Tools
alias media-tools="sudo docker run -w ~/Tools/mediaTools/media -v ${PWD}/media:/media -it --rm media-tools"

# Binaries
alias intelliJ="$HOME/Apps/idea-IC-222.3345.118/bin/idea.sh"
alias file-hider="$HOME/Tools/fileHider-linux"
alias deno="$HOME/.deno/bin/deno"
alias yt-dl="youtube-dl"

# AppImages
alias cura="LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libstdc++.so.6 $HOME/AppImages/Ultimaker-Cura-5.0.0-linux.AppImage"
alias belena="$HOME/AppImages/balenaEtcher-1.10.0-x64.AppImage"
alias arduino="$HOME/AppImages/arduino-ide_2.0.2_Linux_64bit.AppImage"
# alias cura="$HOME/AppImages/Ultimaker-Cura-5.2.1-linux.AppImage"

# Scripts
alias subneti-eth="$HOME/Projects/bashScripts/subnetEth.sh"
alias subnet-wifi="$HOME/Projects/bashScripts/subnetWifi.sh"

# VPN
alias kill-cloak="sudo cyberghostvpn --stop"
alias cloak="sudo cyberghostvpn --traffic --country-code CN --connect"
alias cloak-lite="sudo cyberghostvpn --traffic --country-code US --connect"

# Dot file repo
alias dotfile-backup="/usr/bin/git --git-dir=$HOME/DotFileBackup --work-tree=$HOME"

# VsCode
alias vsc="code"

# Git
alias g="git"
alias gstat="git status"
