# create-website-in-windows-laptop

1. install docker desktop
2. Linux 用 Windows サブシステムを有効にする
3. startmenu-powershell-run as administrator
4. write "dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart" in powershell
5. reboot
6. powershell "dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart"
7. reboot
8. powershell "wsl --set-default-version 2"
9. update to WSL2
10. dawnload "Ubuntu 22.04 LTS"
11. create accaunt in Ubuntu 22.04 LTS
12. 
