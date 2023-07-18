###
https://desktop.github.com/
https://github.com/vtvh/savegame
###
ninite.com
###

# Open Powershell (as Admin still work)
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -y

iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
scoop install git 

scoop install erdtree wget curl curlie vim neovim
scoop bucket add extras
scoop install extras/vscode

Add Visual Studio Code as a context menu option by running:
'reg import "C:\Users\Administrator\scoop\apps\vscode\current\install-context.reg"'
For file associations, run:
'reg import "C:\Users\Administrator\scoop\apps\vscode\current\install-associations.reg"'

# fonts
scoop bucket add nerd-fonts 
scoop install Cascadia-Code   

# Get Vimium settings
git clone https://github.com/vtvh/vimium-settings
start vimium-settings/engines
start vimium-settings/keymaps
start https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en

C:\Users\Administrator\Documents\Assassin's Creed IV Black Flag
F:\Offline Games\Assassins Creed IV Black Flag\save3dmgames

# Side quest
# watch all these and decice to switch to neovim
https://neovim.io/
https://youtu.be/c4OyfL5o7DU
https://www.youtube.com/watch?v=DzNmUNvnB04
https://youtu.be/Mtgo-nP_r8Y

## add vimium