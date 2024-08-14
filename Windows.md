# Chocolatey


```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
>[!NOTE]
>Run terminal as administrator 

# Neovim

```powershell
choco install -y neovim git ripgrep wget fd unzip gzip mingw make

# navigate to config for nvim clone and clone repo
git clone https://github.com/runala/kickstart.nvim.git nvim
```

# Languages

## Golang & Python
```powershell
choco install -y golang python
```
## Csharp

[Install Dotnet SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

## Rust

[Getting started](https://www.rust-lang.org/learn/get-started)

# Tools
