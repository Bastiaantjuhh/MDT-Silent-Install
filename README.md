Software | Command
--- | ---
7 Zip | ```7z2107-x64.msi /q INSTALLDIR="C:\Program Files\7-Zip"```
Bounjour | ```BonjourPSSetup.exe /quiet /qn```
Cryptomator | ```Cryptomator-1.6.10-x64.msi /quiet /qn```
Choco | ```powershell.exe "Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex"```
CrystalDiskInfo | ```CrystalDiskInfo8_16_4.exe /SILENT```
CyberDuck | ```Cyberduck-Installer-8.3.3.37544.exe /install /quiet```
Exif Tool | ```ExifTool_install_12.41_64.exe /VERYSILENT```
Filebot | ```FileBot_4.9.6_x64.msi /qb```
Git | ```Git-2.36.0-64-bit.exe /SILENT /SUPPRESSMSGBOXES /NORESTART /NOCANCEL```
Git LFS | ```git-lfs-windows-v3.1.4.exe /SILENT /SUPPRESSMSGBOXES /NORESTART /NOCANCEL```
Google Chrome Enterprise | ```MsiExec.exe /i googlechromestandaloneenterprise64.msi /qn```
GreenShot | ```Greenshot-INSTALLER-1.2.10.6-RELEASE.exe /VERYSILENT```
NodeJS | ```node-v16.14.2-x64.msi /qb```
PowerShell 7.2 | ```msiexec.exe /package PowerShell-7.2.2-win-x64.msi /quiet ADD_EXPLORER_CONTEXT_MENU_OPENPOWERSHELL=1 ENABLE_PSREMOTING=1 REGISTER_MANIFEST=1 USE_MU=1 ENABLE_MU=1```
PuTTY | ```MsiExec.exe /i putty-64bit-0.76-installer.msi /qn```
RemoteDesktopPlus | ```RemoteDesktopPlus.msi /quiet /qn```
TreeSize | ```TreeSizeFreeSetup.exe /verysilent```
VirtIO Guest Tools | ```virtio-win-guest-tools.exe /install /quiet```
VMware Workstation Pro | ```VMware-workstation-full-16.2.3-19376536.exe /s /v /qn EULAS_AGREED=1 SERIALNUMBER=ZF71R-DMX85-08DQY-8YMNC-PPHV8```
VNC Viewer | ```VNC-Viewer-6.22.315-Windows-en-64bit.msi /quiet /qn```
Windows Exporter for Promotheus | ```msiexec /i windows_exporter-0.18.1-amd64.msi ENABLED_COLLECTORS="cpu,cpu_info,cs,logical_disk,net,system,service,textfile" LISTEN_PORT=9182```
WireGuard Client | ```wireguard-amd64-0.5.3.msi /quiet /qn```