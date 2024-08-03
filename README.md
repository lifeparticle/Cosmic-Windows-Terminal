1. Download [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701)

2. poshgit

```shell
choco install poshgit
```

3. Download [Zoomit](https://docs.microsoft.com/en-us/sysinternals/downloads/zoomit)
```
zoom mode -> ctrl + 1
zoom in -> mouse scroll up
zoom out -> mouse scroll down
start drawing -> left click
stop drawing -> right click
start drawing not in zoom mode -> ctrl + 2
```
[Shortcuts](https://learn.microsoft.com/en-us/sysinternals/downloads/zoomit#shortcuts)

3. Download [Powershell](https://github.com/powershell/powershell)

4. Set PowerShell as your default from settings

![image](https://user-images.githubusercontent.com/1612112/186836850-b955f13b-d27c-4066-9cf8-1c8b40a44dc4.png)

5. Hide Windows PowerShell in `setting.json` file

```json
"hidden": true
```

6. Move PowerShell to the top in `setting.json` file

7. In the terminal run

```shell
wsl --install
```

8. Intall Ubuntu

```
wsl --install -d Ubuntu
```

or

Downlaod [Ubuntu](https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV). To install search and click **Ubuntu**

9. Show Ubuntu in `setting.json` file

10. Download [Caskaydia Cove Nerd Font](https://www.nerdfonts.com/font-downloads) and drop the into `C:\Windows\Fonts`

11. [Oh My Posh](https://ohmyposh.dev/docs)

```shell
winget install JanDeDobbeleer.OhMyPosh -s winget
```

12. Set the Caskaydia Cove Nerd Font

```
CaskaydiaCove NF
```

13. You may have to create the folder `PowerShell` and the file `Microsoft.PowerShell_profile.ps1`

```shell
echo $PROFILE
echo 'test' > C:\Users\***\Documents\PowerShell\Microsoft.PowerShell_profile.ps1
```

14. Open file `Microsoft.PowerShell_profile.ps1` and add the following line. Read more [here](https://ohmyposh.dev/docs/installation/prompt)

```
oh-my-posh init pwsh | Invoke-Expression
```

15. Set Terminal Transparency

```
ctrl + shift + scroll up/down
```

# Resources
1. [How to make the ultimate Terminal Prompt on Windows 11](https://www.youtube.com/watch?v=VT2L1SXFq9U)
