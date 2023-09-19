## Customizing PowerShell with OhMyPosh and jonnychipz Theme

This guide will help you customize your PowerShell terminal using OhMyPosh with the lovely jonnychipz theme. Here's how you can achieve a stylish and efficient terminal setup.

### Prerequisites

Before you begin, ensure you have the following prerequisites:

1. [Install PowerShell](https://github.com/PowerShell/PowerShell/releases): Make sure you have the latest version of PowerShell installed.

2. [Install OhMyPosh](https://ohmyposh.dev/): Use the Windows Package Manager (winget) to install OhMyPosh.

   ```powershell
   winget install JanDeDobbeleer.OhMyPosh -s winget
   ```

3. [Install Caskaydiacove Nerd Font](https://www.nerdfonts.com/font-downloads): Download and install the Nerd Font for better icon support.
** To change font in windows terminal go to apperance
   
### Installing the jonnychipz Theme

To install the jonnychipz theme for OhMyPosh, follow these steps:

1. Install the jonnychipz theme using winget:

   ```powershell
   winget install jonnychipz.OhMyPosh -s winget
   ```

2. Configure OhMyPosh to use the jonnychipz theme. Create a configuration file by running:

   ```powershell
   oh-my-posh init pwsh --config 'C:/Users/Posh/jonnychipz.omp.json' | Invoke-Expression
   ```

### Making OhMyPosh Start Automatically

To ensure that OhMyPosh and the jonnychipz theme start automatically with your PowerShell, follow these steps:

1. Open your PowerShell profile in Notepad:

   ```powershell
   notepad $PROFILE
   ```

2. Add the following lines to your PowerShell profile script:

   ```powershell
   oh-my-posh init pwsh --config 'C:/Users/Posh/jonnychipz.omp.json' | Invoke-Expression
   Set-PSReadLineOption -PredictionSource History
   Set-PSReadLineOption -PredictionViewStyle ListView
   ```

3. Save the changes and close Notepad.

Now, every time you open PowerShell, it will use the jonnychipz theme, and you'll have improved predictions and suggestions.

## POWERSHELL 1.1 (optional)

### Initialize OhMyPosh and apply the jonnychipz theme
```powershell
oh-my-posh init pwsh | Invoke-Expression
oh-my-posh prompt init pwsh --config https://raw.githubusercontent.com/JanDeDobbeleer/oh-my-posh/v$(oh-my-posh --version)/themes/jonnychipz.omp.json | Invoke-Expression
```

### Configure PSReadLine options
```powershell
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
```
### use this
https://github.com/devblackops/Terminal-Icons


### More Themes

If you want to explore more themes for OhMyPosh, you can find a variety of options [here](https://ohmyposh.dev/docs/themes).

### if you like the work hit star ⭐

## Conclusion

With OhMyPosh and the jonnychipz theme, you can elevate your PowerShell terminal's appearance and functionality. Enjoy coding with style and efficiency!

Feel free to customize the readme.md further and add any additional information or screenshots to make it more informative and visually appealing.
