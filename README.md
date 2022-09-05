# Omnipresent Binaries, well almost...
<img src="https://omnibins.github.io/assets/logo.png" height="250">

All the different binaries and libraries can be found behind a fancy frontend here: https://omnibins.github.io/

This repo holds the YML files that are used by the fancy frontend. If you want to make a submission, you are in the right place.


A huge "thank you" to the teams over at [LOLBAS](https://lolbas-project.github.io/) and [GTFOBins](https://gtfobins.github.io/). I'm truly standing on the shoulder of giants, which allowed me to clone their projects (sometimes ~~almost~~ word for word) as boilerplate and get started in no time, while maintaining the awesome look & functionality we got accustomed to.  


## Goal

This project collects third-party binaries and libraries commonly found in business environments which can be leveraged to execute commands, manipulate files, bypass AppLocker and much more.

## Use cases

Isn't the abuse of such files and libraries super niche and circumstantial? Well.. yeah, it probably is. Regardless of that I like ~~hoarding~~ collecting this information because I find it interesting and you know.. just in case.

* Bypassing AppLocker
* Escaping from Kiosks / Sandboxes
* Escalation of priviliges
* Tiny bit more stealthy

## Criteria

A OmniBin Binary/Library must:
* Be somewhat common in a business environment
* Have extra "unexpected" functionality. It is not interesting to document intended use cases
  * Exceptions are application whitelisting bypasses
* Have functionality that would be useful to an APT or red team

Interesting functionality can include:
* Executing code
  * Arbitrary code execution
  * Pass-through execution of other programs or libraries (via a OmniBin)
* File operations
  * Downloading
  * Upload
  * Copy
  * Browse
* Persistence
  * Pass-through persistence utilizing existing LOLBin
  * Persistence (e.g. hide data in ADS, execute at logon)
* UAC bypass
* Credential theft
* Dumping process memory
* Log evasion/modification
* DLL side-loading/hijacking without being relocated elsewhere in the filesystem

## Contributing

Guidelines are not done yet. Should you want to get started anyway, feel free to do so. I've jotted down some Applications which could be interesting, but didn't review myself yet for "unexpected" functionality.

<details><summary>View</summary>
<p>
* Spotify
* iTunes
* Winamp
* Google Earth
* Slack
* AVs
* Blender
* Gimp
* Inkscape
* Paint.NET
* 7-Zip
* Winrar
* WinZip
* OpenVPN
* GlobalProtect
* Adobe Suite
* Adobe Acrobat Reader
* Teams?
* Skype
* Zoom
* WebEx
* SAP
* Chrome
* Firefox
* Notion
* Notepad++
* Sublime
* VSCode
* GitHub Desktop
* SourceTree
* Git
* Figma
* CCleaner
* VLC
* WhatsApp for PC
* IrfanView
* Facebook Desktop
* TeamViewer
* AnyDesk
* Audacity
* Keepass
* LibreOffice
* Open Office
* Krita
* Darktable
* RawTherapee
* VMware Player
* Virtual Box
* Citrix Workspace
* Shotcut
* FileZilla
* Thunderbird
* TrueCrypt / VeraCrypt
* OpenSSL
* PuTTY
* XAMPP
</p>
</details>