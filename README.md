# my-customization-terminal
powershell customization

install the OhMyPosh command
winget install JanDeDobbeleer.OhMyPosh -s winget

ON windows terminal
USING powrshell latest version
[powershell](https://github.com/PowerShell/PowerShell/releases)

* to install another change the name in [name]
winget install [name].OhMyPosh -s winget
oh-my-posh init pwsh --config 'C:/Users/Posh/[name].omp.json' | Invoke-Expression

* i love ❤️ jonnychipz theme
winget install jonnychipz.OhMyPosh -s winget

* to make it alwayas run in start put 3 line in this file using notepad
notepad $PROFILE
oh-my-posh init pwsh --config 'C:/Users/Posh/jonnychipz.omp.json' | Invoke-Expression
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
🎉

* IN PROFILE PUT THIS COMMANDS POWERSHELL NORMAL 1.1
oh-my-posh init pwsh | Invoke-Expression
oh-my-posh prompt init pwsh --config https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/v$(oh-my-posh --version)/themes/jonnychipz.omp.json | Invoke-Expression

Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView

* more themes
https://ohmyposh.dev/docs/themes


IMPORTANT
Install Caskaydiacove Nerd Font 
https://www.nerdfonts.com/font-downloads



