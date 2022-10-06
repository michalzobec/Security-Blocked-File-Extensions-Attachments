# List of blocked file extensions

<a name="documenttitle"></a>

Copyright &copy; 2021-2022 ZOBEC Consulting. All Rights Reserved.

## About this repository

This repository contains list of unwanted or suspicious file extensions in Windows environment. You can use in for example Microsoft OneDrive, Microsoft SharePoint, or Microsoft Exchange.

[*Back to top*](#documenttitle "Top of the document")

## The background of the creation of this repository

During implementation of OneDrive and SharePoint, I wanted to implement blocking of unwanted or suspicious file extensions. I make list of blocked type of files and after finish I got think publish him on my web.

In time I had to make some extensions of this list, because list is still not perfect and some file extensions will be good to add to block list. But in this phase I had problem, because actual list it was only as article on my web, but in SharePoint you must enter list of extensions as plain text list, with one file extension in one row. And tracking of changes it was too complicated.

So I moved this list to this repository, where I can better and more easy track of any change.

[*Back to top*](#documenttitle "Top of the document")

## Table with blocked file extensions

File type | Extension | Reson for blocking
----------- | ------- | -----------------
Application files in Windows | com exe dll ocx | Potentially dangerous. Unwanted to save on OneDrive.
PowerShell script files | ps1 ps1xml ps2 ps2xml psc1 psc2 msh msh1 msh2 mshxml msh1xml msh2xml | Potentially dangerous. Unwanted to save on OneDrive.
Windows JavaScript files | js jse | Potentially dangerous. Unwanted to save on OneDrive.
Windows Visual Basic Script files | vbs vb vbe | Potentially dangerous. Unwanted to save on OneDrive.
Windows Commandline script files | cmd bat | Potentially dangerous. Unwanted to save on OneDrive.
HTML Application (Internet Explorer) | hta | Potentially dangerous. Unwanted to save on OneDrive.
Windows Installation file | inf | Potentially dangerous. Unwanted to save on OneDrive.
Windows Registry configuration file | reg | Potentially dangerous. Unwanted to save on OneDrive.
MS-DOS configuration link | pif | Potentially dangerous. Unwanted to save on OneDrive.
Windows Screensaver file | scr | Potentially dangerous. Unwanted to save on OneDrive.
Windows Control Panel applet file | cpl | Potentially dangerous. Unwanted to save on OneDrive.
Windows Explorer command file | scf | Potentially dangerous. Unwanted to save on OneDrive.
Microsoft Management Console file | msc | Potentially dangerous. Unwanted to save on OneDrive.
Windows Group Policy file | pol | Potentially dangerous. Unwanted to save on OneDrive.
Windows Help files | hlp chm | Potentially dangerous. Unwanted to save on OneDrive.
Windows Host Script files | ws wsf wsc wsh | Potentially dangerous. Unwanted to save on OneDrive.
Java archive / Java class file | jar | Potentially dangerous. Unwanted to save on OneDrive.
Various file archive file types | rar z bz2 cab gz tar ace | Unused (compressed) archive file types. Allowed file types is only ZIP and 7z (7-Zip). Other file types are not used to ensure compatibility and unification of archive file types used.
Windows Installer files | msi msp mst | No any reason for save on OneDrive.
Windows Update files | msu | No any reason for save on OneDrive.
Windows Provisioning Package file | ppkg | Potentially dangerous. Unwanted to save on OneDrive.
SQL Server backup file | bak | No any reason for save on OneDrive.
Temporary files | tmp | It can create many write operations and overload OneDrive and Internet line unnecessarily. No any reason for save on OneDrive.
Outlook offline file | ost | No any reason for save on OneDrive.
Outlook data file | pst | No any reason for save on OneDrive.
Apple macOS installation file | pkg | No any reason for save on OneDrive.
ISO Image files | iso img | File with image of the CD/DVD media. A potentially large file in the order of tens of GB. Unwanted to save on OneDrive.
Hyper-V Virtual Hard Disk files | vhd vhdx | It can create many write operations and overload OneDrive and Internet line unnecessarily. No any reason for save on OneDrive.
ClickOnce Deployment file | application | Potentially dangerous. Unwanted to save on OneDrive.
Universal lock extension file | lock lck | Lock file used by various applications. It is undesirable to use OneDrive as storage for running applications. It can create many write operations and overload OneDrive and Internet line unnecessarily. No any reason for save on OneDrive.
C# source code files | sln cs csproj resx config resources pdb manifest | It is not desirable to store source codes on OneDrive. Source code repositories such as GitHub or Azure DevOps are used for this purpose. No any reason for save on OneDrive.
Audio file | mp3 wma | Possible source of copyright issues. Unwanted to save on OneDrive.
Microsoft Office Word legacy file format | doc dot wbk | Unwanted to save on OneDrive.
Microsoft Office Excel legacy file format | xls xlt xlm xla | Unwanted to save on OneDrive.
Microsoft Office PowerPoint legacy file format | ppt pot pps | Unwanted to save on OneDrive.
Microsoft Office Access legacy file format | ade adp mdb cdb mda mdn mdt mdf mde ldb | Unwanted to save on OneDrive.
Microsoft Works file format | wps | Unwanted to save on OneDrive.
Microsoft Office Excel Add-in files | xlsb xlam xll xlw | Potentially dangerous. Unwanted to save on OneDrive.
Microsoft PowerPoint Add-in file | ppam |  Unwanted to save on OneDrive.

[*Back to top*](#documenttitle "Top of the document")

## Documentation (all documents)

* [Main document (ReadMe)](README.md).
* [List of blocked files in plain text file](list-of-blocked-file-extensions.txt).
* [History](HISTORY.md).
* [License](LICENSE.).

[*Back to top*](#documenttitle "Top of the document")

## Links

- [Microsoft 365/Office 365: OneDrive: Zakázané typy souborů (blocked file types) na OneDrive](https://www.michalzobec.cz/microsoft-365-office-365-onedrive-zakazane-typy-souboru-blocked-file-types-na-onedrive-8199)
- [SwiftFilter/Audit-ExternalSuspiciousAttachments.txt](https://github.com/SwiftOnSecurity/SwiftFilter/blob/master/Audit-ExternalSuspiciousAttachments.txt)
- [Awesome Windows Domain Hardening](https://github.com/PaulSec/awesome-windows-domain-hardening#initial-foothold)
- [CryptoBlocker - A script to deploy File Server Resource Manager and associated scripts to block infected users](https://github.com/nexxai/CryptoBlocker)
- [Anti-Ransomware File System Resource Manager Lists](https://fsrm.experiant.ca/) - [API: Get file list](https://fsrm.experiant.ca/api/v1/get)
