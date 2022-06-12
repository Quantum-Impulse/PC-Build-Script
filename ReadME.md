# Choco PC script

 This is a script that used Chocolatey to install apps on windows because it takes to much time to download stuff when building PCs on a time crunch 🏃‍♂️

## Description

Only works with windows and must have Chocolatey installed to work

## Getting Started

### Dependencies

* Chocolatey
* Windows 10 or ll

### Installing

* Open PowerShell as a administrator and paste in the following commmand
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Executing program

```
```

```

```