---
Name: Notepad++
Binary: gup.exe
Description: Notepad++ is a text and source code editor for use with Microsoft Windows.
Author: ZeMooX
Created: 2022-09-07
Commands:
  - Command: gup.exe -unzipTo "C:\Windows\System32\cmd.exe" " " " "
    Description: Executes cmd.exe
    Usecase: Execute an arbitrary file using a signed binary.
    Category: Execute
    Privileges: None
    MitreID: T1547
    OperatingSystem: Windows 11,10,8,7
Full_Path:
  - Path: 'C:\Program Files (x86)\Notepad++\updater\gup.exe'
Code_Sample: 
  - Code: https://github.com/LuxNoBulIshit/test.inf/blob/main/inf
Detection:
  - Sigma: https://github.com/SigmaHQ/sigma/blob/a8a0d546f347febb0423aa920dbc10713cc1f92f/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml
Acknowledgement:
  - Person: ZeMooX
    Handle: '@'
---
