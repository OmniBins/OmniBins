---
Name: Krita
Binary: kritarunner.exe
Description: Krita is a free and open-source raster graphics editor designed primarily for digital painting and 2D
Author: ZeMooX
Created: 2022-09-06
Commands:
  - Command: kritarunner.exe -s evil-script -f evil-func-name [script argument(s)]
    Description: Executes a provieded Python script. The .py has to be omitted from the filename. If no function name is provided, the __main__ function gets called.
    Usecase: Execute a python script with Kritarunner as parent.
    Category: Execute
    Privileges: User
    MitreID: T1547
    OperatingSystem: Windows 11,10,8,7
Full_Path:
  - Path: 'C:\Program Files\Krita (x64)\bin\kritarunner.exe'
Code_Sample: 
  - Code: https://github.com/LuxNoBulIshit/test.inf/blob/main/inf
Detection:
  - Sigma: https://github.com/SigmaHQ/sigma/blob/a8a0d546f347febb0423aa920dbc10713cc1f92f/rules/windows/process_creation/process_creation_lolbins_suspicious_driver_installed_by_pnputil.yml
Acknowledgement:
  - Person: ZeMooX
    Handle: '@'
---
