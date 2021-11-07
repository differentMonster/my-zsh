# Terminal Zsh

# Step 1
* install zsh ( Terminal )
** Set as Core terminal

# Step 2
* install oh-my-zsh ( Zsh Plugins Package Manager )
** path = /root/.oh-my-zsh
** customize file = .zshrc

# add plugins into .zshrc after install on ternimal
plugins=(
npm
git
zsh-autosuggestions
zsh-syntax-highlighting
zsh-completions
auto-notify
you-should-use
git-open
)

# link zsh with oh my zsh ( should be automatic after set as main ternimal )
source $ZSH/oh-my-zsh.sh

# Step 3
* install powerlevel9k ( Terminal Theme )
# Setup Theme for powerlevel9k
ZSH_THEME="powerlevel9k/powerlevel9k"

# VSC = Version Control System ( git )
POWERLEVEL9K_VCS_CLEAN_FOREGROUND=017 #navyblue
# Set color base once enter git master
POWERLEVEL9K_VCS_CLEAN_BACKGROUND=red3

# Cheatsheet
dirs -v = fast directroy access location
cat -v = test keypress
