1. [zoomit](https://docs.microsoft.com/en-us/sysinternals/downloads/zoomit)
2. Set your default terminal
3. [powershell](https://github.com/powershell/powershell)
4. Set powershell as your default
![image](https://user-images.githubusercontent.com/1612112/186836850-b955f13b-d27c-4066-9cf8-1c8b40a44dc4.png)
5. Hide windows powershell in `setting.json` file
6. Move powershell to the top in `setting.json` file
7. In the terminal run
```
wsl --install
```
8. Show Ubunto in `setting.json` file
9. [Download](https://www.nerdfonts.com/font-downloads) Caskaydia Cove Nerd Font and drop the into `C:\Windows\Fonts`
10. [Oh My Posh](https://ohmyposh.dev/docs)
```
winget install JanDeDobbeleer.OhMyPosh -s winget
```
11. Set the Caskaydia Cove Nerd Font
12. Profile
```
echo $PROFILE
```
You may have to create the folder `PowerShell` and the file `Microsoft.PowerShell_profile.ps1`
13. Open file `Microsoft.PowerShell_profile.ps1` and add the following line. Read more [here](https://ohmyposh.dev/docs/installation/prompt).
```
oh-my-posh init pwsh | Invoke-Expression
```














# Resources
1. https://www.youtube.com/watch?v=VT2L1SXFq9U
