**Index** ::[Basics](./1-preinstall-basics.md) :: [Backup](./2-preinstall-backup.md) ::
* * *

# Windows Install-Guide

This guide will cover everything you need to know about (re-)installing Microsoft Windows 10/11 on your computer, usually intended for the use of dual-boot. From Backup considerations, Firewall- and Privacy settings to recommendations of useful (and free) tools for essential work.

This guide is intended for the beginner and hobbyist user, and while it may encourage you to dive into some deeper settings, it will always be explained why you should do so. Some optional and extended knowledge is required to do certain things. These comprehensive explanations are contained in the supplementary section and referenced when needed for a better overview.

Every recommendation in this guide is optional and can be ignored or changed for creating a Windows environment that *works for you*. Multiple options are given when available, considering why to use one program or plugin over another.

This guide, however, strongly recommends doing a fresh install of MS Windows 10 and **not** an "upgrade". It means re-formatting your main hard disc or hard disc partition and do a clean installation of MS Windows 10/11. History has shown that while an upgrade installation works, it tends to lead to a much slower and unstable environment than doing the extra steps of a fresh install.

> :large_blue_diamond: **Note on Windows 11 and dual-boot**
>
> While the Linux Bootloader may support **Secure-Boot and TPM**, it is not guaranteed. By default, both are required in Windows 11. The checks can be disabled before upgrading to or installing Windows 11. Please keep in mind that the Windows 11 Installation tries very hard to make you create a Microsoft Account for login instead of a Local Account (or outright disables Local Accounts in Windows 11 Home). The Windows Login Service *Windows Hello* may not work if you disable TPM, and therefore you may not be able to log in. 
>
> It is therefore required to: 
>
> - Own a copy of Windows 10 or Windows 11 Pro
> - Install Windows 11 and create a Local Account for Login *or*
> - Make sure to have (converted to) a Local Account in Windows 10 before upgrading to Windows 11
>
> More information can be found [here](https://docs.microsoft.com/en-us/windows/security/information-protection/tpm/tpm-recommendations).
