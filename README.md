# WindowsEnum

A Powershell Privilege Escalation Enumeration Script.

This script automates most of what is detailed in my Windows Privilege Escalation guide [here](https://www.sploitspren.com/2018-01-26-Windows-Privilege-Escalation-Guide/).

## Usage

To run the quick standard checks.

```powershell
.\WindowsEnum.ps1
```

Directly from CMD

```
powershell -nologo -executionpolicy bypass -file WindowsEnum.ps1
```

Extended checks will search for config files, various interesting files, and passwords in files and the registry, etc. It will take some time so be patient.

```powershell
.\WindowsEnum.ps1 extended
```

```
powershell -nologo -executionpolicy bypass -file WindowsEnum.ps1 extended
```
