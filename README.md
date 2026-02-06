# Install WSL on Windows 11 Using PowerShell
```powershell
Enable-WindowsOptionalFeature -Online -FeatureName "Microsoft-Windows-Subsystem-Linux"
```

# Spin up another instance of Distro with Custom Name
```powershell
wsl --install -d Ubuntu --name ubuntu-react
```
