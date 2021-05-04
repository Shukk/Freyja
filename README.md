# Freyja Project - Hacktools in a nutshell

## Nmap

Free and open-source network scanner used to discover hosts and services on a computer network by sending packets and analyzing the responses. (https://github.com/nmap/nmap)

## Secretsdump

Uses different techniques to dump secrets from the remote machine without executing any agent on it. (https://github.com/SecureAuthCorp/impacket/blob/master/impacket/examples/secretsdump.py)

## Zenmap

GUI for nmap. (https://nmap.org/zenmap/)

## Metasploit

Framework providing tools for developing and executing exploit code against a remote target machine. (https://github.com/rapid7/metasploit-framework)

## Burpsuite

Software used to perform security testing of web applications. (https://portswigger.net/burp)

## Mimikatz

Tool used to extract plaintexts passwords, hash, PIN code and kerberos tickets from memory. It can also performs pass-the-hash, pass-the-ticket or build Golden tickets. (https://github.com/gentilkiwi/mimikatz)

## BloodHound

Uses graph theory to reveal relationships within an Active Directory domain to discover attack paths. (https://github.com/BloodHoundAD/BloodHound)

It supports two collectors: ***Sharphound*** (collects data from a local Active Directory) and ***Azurehound*** (collects data from an Azure tenant).

## ADRecon

Extracts and combines various artefacts out of an Active Directory environment and put it in an Excel file. (https://github.com/sense-of-security/ADRecon)

## Pingcastle

Tool to audit the risk level of an Active Directory infrastructure and check for vulnerable practices. Can be run as a normal domain user, no install required. https://github.com/vletoux/pingcastle

## CrackMapExec

Post-exploitation tool that helps automate assessing the security of large Active Directory networks. (https://github.com/byt3bl33d3r/CrackMapExec)

## Powerview

PowerShell recon tool using PowerShell AD hooks and underlying Win32 API functions to exploit Windows domain functionality. (https://github.com/PowerShellMafia/PowerSploit/tree/master/Recon)

## Powersploit (no longer maintained)

Collection of PowerShell modules that can be used by pentesters during multiple phases of the Killchain. (https://github.com/PowerShellMafia/PowerSploit)

## PowerShell Empire (no longer maintained)

Post-exploitation framework that includes a Powershell agent. It can perform privilege escalation, network and host reconnaissance, lateral movement and credentials gathering. (https://github.com/EmpireProject/Empire)

Fork by BC-Security : https://github.com/BC-SECURITY/Empire (maintained). Other alternatives are Covenant (https://github.com/cobbr/Covenant), Faction (https://github.com/FactionC2/Faction) or Mythic (https://github.com/its-a-feature/Mythic).

## Nishang

Framework and collection of Powershell scripts and payloads. (https://github.com/samratashok/nishang)

## PSAttack

Combines some of the best projects in the infosec Powershell community (PowerSploit, Nishang, Powercat, Inveigh, Invoke-TheHash) into a custom PowerShell console. (https://github.com/jaredhaight/PSAttack)

## Luckystrike

Tool for creating malicious Office macro documents. (https://github.com/curi0usJack/luckystrike)

## Cobalt Strike

Paid penetration testing software that allows an attacker to deploy an agent on the victim machine which can perform command execution, key logging, file transfer, SOCKS proxying, privilege escalation, mimikatz, port scanning and lateral movement. (https://www.cobaltstrike.com/)

## Responder

LLMNR, NBT-NS and mDNS poisoner. It will answer to specific NBT-NS (NetBIOS Name Service) queries based on their name suffix. By default, the tool will only answer to File Server Service request, which is for SMB. (https://github.com/lgandx/Responder)

## ProcessHacker

Process and service viewer that shows a huge number of details about running processes. (https://github.com/processhacker/processhacker)

## Dirsearch

Command-line tool designed to brute force directories and files in webservers. A dirbuster like but without GUI. (https://github.com/maurosoria/dirsearch)

## LaZagne

Credential stealer: retrieve lots of passwords stored on a local computer (browsers, databases, dumps from memory...). (https://github.com/AlessandroZ/LaZagne)

## PowerUpSQL

Powershell toolkit for attacking SQL server. It can perform SQL Server discovery, weak configuration auditing, privilege escalation on scale, and post exploitation actions such as OS command execution. (https://github.com/NetSPI/PowerUpSQL)

## Rubeus

Toolkit for Kerberos interaction and abuses. (https://github.com/GhostPack/Rubeus)

## UACME

Toolkit that incorporates numerous UAC bypass techniques for Windows7 - Windows10. (https://github.com/hfiref0x/UACME)

## KeeFarce

Using DLL injection to extract KeePass 2.x password database information from memory into a CSV. (https://github.com/denandz/KeeFarce)

## KeeThief

Walks the heap looking for KeePass master key and injects shellcode to decrypt information. (https://github.com/GhostPack/KeeThief)

## Social Engineer Toolkit

Pentest framework designed for social engineering. (https://github.com/trustedsec/social-engineer-toolkit)
