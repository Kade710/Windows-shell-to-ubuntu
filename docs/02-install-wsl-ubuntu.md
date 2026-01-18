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
