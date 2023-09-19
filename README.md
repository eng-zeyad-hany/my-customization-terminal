# my-customization-terminal
powershell customization




OLD WAY TO INSTALL OH_MY_POSH
Import-Module oh-my-posh
Install-Module oh-my-posh -Scope CurrentUser
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
Install-Module PSReadLine -Force

notepad $PROFILE

IN PROFILE PUT THIS COMMANDS
oh-my-posh prompt init pwsh --config https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/v$(oh-my-posh) --version)/themes/mt.omp.json | Invoke-Expression
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView




https://ohmyposh.dev/docs/themes


IMPORTANT
Install Caskaydiacove Nerd Font 
https://www.nerdfonts.com/font-downloads



