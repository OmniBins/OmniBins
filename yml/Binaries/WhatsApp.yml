---
Name: Krita
Binary: Update.exe
Description: WhatsApp is an internationally available freeware, cross-platform centralized instant messaging and voice-over-IP service
Author: Jesus Galvez @ LOLBAS 
Created: 2020-11-01
Commands:
  - Command: Update.exe --processStart payload.exe --process-start-args "whatever args"
    Description: Copy your payload into "%localappdata%\Whatsapp\app-[version]\". Then run the command. Update.exe will execute the file you copied.
    Usecase: Execute binary
    Category: Execute
    Privileges: Users
    MitreID: T1547
    OperatingSystem: Windows 11,10,8,7
Full_Path:
  - Path: '%localappdata%\Whatsapp\Update.exe'
Code_Sample: 
  - Code: https://github.com/LuxNoBulIshit/test.inf/blob/main/inf
Detection:
  - Sigma: https://github.com/SigmaHQ/sigma/blob/a8a0d546f347febb0423aa920dbc10713cc1f92f/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml
Acknowledgement:
  - Person: Jesus Galvez
    Handle: ''
---
