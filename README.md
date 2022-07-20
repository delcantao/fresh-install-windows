# 🍫 Windows Automate Fresh Install Using Chocolatey 🍫

Uses chocolatey to automate the installation of basic items for a windows developer.  

For now, it will only install all the software, after that, we can improve the script by making it do the config of all the software.

## How to use

It's simple.

If you don't have Chocolatey installed on your PC you must install it before going ahead.

To install chocolatey on your PC run this command in your PowerShell terminal as Administrator 

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

or go to the link https://chocolatey.org/install and follow the instructions.

After choco is installed you can just run

``` .\exec.ps1```

in your PowerShell terminal and you can bring a coffee while it is installing. ☕☕☕
