---
title: Powershell - 3 commands to rule them all
date: 2023-04-17 21:00
categories: [windows,Powershell]
tags: [windows,powershell] #should always be lower case
---

# PowerShell - 3 commands to rule them all

powershell commands are called cmdlet and follow the VERB-NAON structure
before starting to use, run - update-help

#### type of commands
get - call to get info, read only action
set - change things

#### you need just 3 commands to master powershell
```powershell
get-command
get-help
get-member # what type of object are we dealing with
```

```powershell
get-command * # will list all commands available in the system
get-command *process* # list all related
```
#### if not sure what the cmdlet dose use - get-help start-process
```powershell
Get-Date # display only some properties, not all of them, what powershell thinks you want to see
Get-Date | Get-Member # evaluate the cmdlet - get the type of object that is returned to us
Get-Date | Format-List # will show all the properties of the object
```

```powershell
Get-Random | Get-Member # an example of a simple cmdlet with simple properties
```

if not sure what cmdlet, just run a google search like "powershell get file properties" - you find for example Get-ItemProperty
run get-help Get-ItemProperty to verife this is what you are looking for, and you can run it with the examples parameter... 
```powershell
Find-Module -tag telegram # powershell has modules that can be installed to it
```
