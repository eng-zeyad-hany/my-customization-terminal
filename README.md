# my-customization-terminal
powershell customization

Install-Module oh-my-posh -Scope CurrentUser

notepad $PROFILE

Import-Module oh-my-posh
oh-my-posh prompt init pwsh --config https://raw.githubusercontent.com/Jan... --version)/themes/mt.omp.json | Invoke-Expression

https://ohmyposh.dev/docs/themes

Set-ExecutionPolicy -ExecutionPolicy Unrestricted

Install Caskaydiacove Nerd Font 
https://www.nerdfonts.com/font-downloads

Install-Module PSReadLine -Force

Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
