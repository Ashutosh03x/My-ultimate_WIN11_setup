## 👾 Terminal + Fastfetch

Minimal and aesthetic terminal setup with Fastfetch
---
> [!NOTE] 
> If you just want the config for Fastfetch then just paste the config where **your** Fastfetch config is located. If you have a PowerShell profile then just add your location and other stuff in your profile yourself as idk what you got.
>
> If you see **"execution of scripts is disabled on this system"**, don’t panic! Just open PowerShell as Administrator and run: 
> `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`
>
> Also if you notice that the ASCII art is not showing then try editing `"source": "C:/Users/%USERPROFILE%/.config/fastfetch/ascii.txt"` to `"source": "%USERPROFILE%/.config/fastfetch/ascii.txt"`. That should fix it. [**Credits**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/issues/1#issue-3498937609).
>
> If you want to add FastFetch to CMD as well, then please check out this [**issue**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/issues/9#issue-3958846174). Big thanks to [**Augtive85YT**](https://github.com/Augtive85YT).
 
- Fastfetch is a neofetch-like tool for fetching system information and displaying it in a visually appealing way. It is written mainly in C, with a focus on performance and customizability.

## 📂Files Included

- Windows Terminal config &rarr; [config.jsonc](./config.jsonc)
- Custom ASCII &rarr; [ascii.txt](./ascii.txt)
- PowerShell profile &rarr; [Powershell_profile.ps1](/PowerShell/Microsoft.PowerShell_profile.ps1)
---
**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://youtu.be/z3NpVq-y6jU) if you want your terminal to look 1:1 to mine.
- Install [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases) and I believe you already got the **Windows terminal** installed.
- Copy the config file for your Terminal [**here**](/Terminal/settings.json), PowerShell profile from [**here**](/PowerShell/Microsoft.PowerShell_profile.ps1) and Fastfetch config from [**here**](/Fastfetch/)
- Remove the codes from the settings.json file in **your terminal** and paste the one you just copied from above. Do the same thing for your PowerShell profile.
- Create a **.config** *hidden* file in your C:\Users\%USERPROFILE% and create a folder called **fastfetch** inside. Copy the config and ascii code you just downloaded and paste it in that folder.
- Change the %USERPROFILE% from the config file in the fastfetch folder and the PowerShell profile with **your username**..
- Restart your terminal and your done. If this feel complicated just watch the [**setup video**](https://youtu.be/z3NpVq-y6jU).
---

Credit: [__**SleepyCatHey🥹💙**__](https://www.youtube.com/@SleepyCatHey) 

