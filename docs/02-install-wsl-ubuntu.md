# Istall WSL + Ubuntu

## Install WSL
Open PowerShell (Admin):

## scripts/powershell/verify-wsl.ps1 (starter)
```powershell
Write-Host "WSL status:"
wsl --status
Write-Host ""
Write-Host "Installed distros:"
wsl -l -v
Write-Host ""
Write-Host "Ubuntu uname:"
wsl -d Ubuntu -- uname -a

---

``` powershell
wsl.exe --install Ubuntu
hostname -V  3.XX
whoami  account username
build-essential git curl unzip ca-certificates
cat /etc/os-release   Ubuntu 24.XX.XX LTS
install --reinstall apt  //I was missing some packages//
