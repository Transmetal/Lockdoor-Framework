# Changelog 📌  :
  #### Version v2.3 IS OUT !! 

        - Fixing some CI 

        - making a more stable version 

        - new docker iaage build

        - adding packages for each supported distros

# Versions 


#### 06/2021 : 2.3

- Config file checking.
- Updating the tools.
- Showing the current version of Lockdoor by -v arg.
- checking the version and asking for possible update.
- Making it easier to customize.
- No added tools for the moment.
- Fixing the docker misconfiguration, the docker version now works perfectly.

    - Information Gathring Tools (21)
    - Web Hacking Tools(15)
    - Reverse Engineering Tools (15)
    - Exploitation Tools (6)
    - Pentesting & Security Assessment Findings Report Templates (6)
    - Password Attack Tools (4)
    - Shell Tools + Blackarch's Webshells Collection (4)
    - Walk Throughs & Pentest Processing Helpers (3)
    - Encryption/Decryption Tools (2)
    - Social Engineering tools (1)
    - All you need as Privilege Escalation scripts and exploits

#### 03/2020 : 2.2.3
   - Information Gathring Tools (21)
   - Web Hacking Tools(15)
   - Reverse Engineering Tools (15)
   - Exploitation Tools (6)
   - Pentesting & Security Assessment Findings Report Templates (6)
   - Password Attack Tools (4)
   - Shell Tools + Blackarch's Webshells Collection (4)
   - Walk Throughs & Pentest Processing Helpers (3)
   - Encryption/Decryption Tools (2)
   - Social Engineering tools (1)
   - All you need as Privilege Escalation scripts and exploits
   - Working on Kali,Ubuntu,Arch,Fedora,Opensuse and Windows (Cygwin)

# Overview 📙 :

*LockDoor* is a Framework aimed at **helping penetration testers, bug bounty hunters And cyber security engineers**.
This tool is designed for Debian/Ubuntu/ArchLinux based distributions to create a similar and familiar distribution for Penetration Testing. But containing the favorite and the most used tools by Pentesters.
As pentesters, most of us has his personal ' /pentest/ ' directory so this Framework is helping you to build a perfect one.
With all of that ! It automates the Pentesting process to help you do the job more quickly and
easily.

# Features 📙 :

## Pentesting Tools Selection 📙 :

   - **Tools**: **Lockdoor** doesn't contain all pentesting tools , let's be honest ! Who ever used all the Tools you find on all those Penetration Testing distributions ? Lockdoor contains only the favorite and the most used tools by Pentesters.


   - **what Tools**: the tools contains **Lockdoor** are a collection from the best tools on Kali,Parrot Os and BlackArch. Also some private tools from some other hacking teams like InurlBr, iran-cyber. Without forgetting some cool and amazing tools I found on Github made by some perfect human beings. 


   - **Easy customization**: Easily add/remove tools.

   - **Installation**: You can install the tool automatically using the installer.sh , Manually or by running the Docker Image.

## Resources and cheatsheets 📙 :

   - **Resources**: That's what makes **Lockdoor**, Lockdoor Doesn't contain only tools ! Pentesing and Security Assessment Findings Reports templates, Pentesting walkthrough examples and templates and more.


   - **Cheatsheets**: Everyone can forget something on processing or a tool use, or even some tricks. Here comes the Cheatsheets role ! there are cheatsheets about everything, every tool on the framework and any enumeration,exploitation and post-exploitation techniques.

# Installation 🛠️ :

> **The recommended way to use Lockdoor is by pulling the Docker Image so you will not have
to worry about dependencies issues.**

- Docker Installation

  - Installing requirments
    ```bash
           sudo apt install docker < Debian-based distributions
           sudo dnf install docker < RPM-based distributions
           sudo pacman -S docker < Arch-based distributions
           sudo zypper install docker < OS-based distributions
           sudo yum install docker < RH-based distributions
    ```
  - Running the container
    ```bash
           1. *Pull lockdoor Docker Image:*
                sudo docker pull sofianehamlaoui/lockdoor

    ``` 
    ```bash
           2. *Run fresh Docker container:*
                sudo docker run -it --name lockdoor-container -w /Lockdoor-Framework --net=host sofianehamlaoui/lockdoor

    ```   
    ```bash
           3. *Run Lockdoor Framework*
                sudo lockdoor

    ```                        
    ```bash
           4. *To re-run a stopped container:*
                sudo docker start -i sofianehamlaoui/lockdoor
    ```   
    ```bash
           5. *To open multiple shells inside the container:*
                sudo docker exec -it lockdoor-container bash
    ``` 
- Using LockAller - Lockdoor Installer

     >  **Installing it using the script may take some time depends on the packages already installed on your system.**
            > here you can find a fresh installation on a new debian distro with no pre-installed packages : [11min]
    ```bash
    git clone https://github.com/Transmetal/Lockdoor-Framework && cd Lockdoor-Framework && chmod +x ./install.sh && ./install.sh 
    ```   


# Lockdoor Tools contents 🛠️ :

## **Information Gathering** :mag_right: :

   - Tools:
      - dirsearch : A Web path scanner
      - brut3k1t : security-oriented bruteforce framework
      - gobuster : DNS and VHost busting tool written in Go
      - Enyx : an SNMP IPv6 Enumeration Tool
      - Goohak : Launchs Google Hacking Queries Against A Target Domain
      - Nasnum : The NAS Enumerator
      - Sublist3r : Fast subdomains enumeration tool for penetration testers
      - wafw00f : identify and fingerprint Web Application Firewall
      - Photon : ncredibly fast crawler designed for OSINT.
      - Raccoon : offensive security tool for reconnaissance and vulnerability scanning
      - DnsRecon : DNS Enumeration Script
      - Nmap : The famous security Scanner, Port Scanner, & Network Exploration Tool
      - sherlock : Find usernames across social networks
      - snmpwn : An SNMPv3 User Enumerator and Attack tool
      - Striker :  an offensive information and vulnerability scanner.
      - theHarvester : E-mails, subdomains and names Harvester
      - URLextractor : Information gathering & website reconnaissance
      - denumerator.py : Enumerates list of subdomains
      - other : other Information gathering,recon and Enumeration scripts I collected somewhere.
   - Frameworks:
      - ReconDog : Reconnaissance Swiss Army Knife
      - RED_HAWK : All in one tool for Information Gathering, Vulnerability Scanning and Crawling
      - Dracnmap : Info Gathering Framework

## **Web Hacking** 🌐 :
   - Tools:
      - Spaghetti : Spaghetti - Web Application Security Scanner
      - CMSmap : CMS scanner
      - BruteXSS : BruteXSS is a tool to find XSS vulnerabilities in web application
      - J-dorker : Website List grabber from Bing
      - droopescan : scanner , identify , CMSs , Drupal , Silverstripe.
      - Optiva : Web Application Scanne
      - V3n0M : Pentesting scanner in Python3.6 for SQLi/XSS/LFI/RFI and other Vulns
      - AtScan : Advanced dork Search & Mass Exploit Scanner
      - WPSeku : Wordpress Security Scanner
      - Wpscan : A simple Wordpress scanner written in python
      - XSStrike : Most advanced XSS scanner.
      - Sqlmap : automatic SQL injection and database takeover tool
      - WhatWeb : the Next generation web scanner
      - joomscan : Joomla Vulnerability Scanner Project
   - Frameworks:
      - Dzjecter : Server checking Tool

## **Privilege Escalation** ⚠️ :
   - Tools:
      - Linux  🐧 :
         - Scripts :
            - linux_checksec.sh
            - linux_enum.sh
            - linux_gather_files.sh
            - linux_kernel_exploiter.pl
            - linux_privesc.py
            - linux_privesc.sh
            - linux_security_test
         - Linux_exploits folder
      - Windows |Windows| :
         - windows-privesc-check.py
         - windows-privesc-check.exe
      - MySql :
         - raptor_udf.c
         - raptor_udf2.c

## **Reverse Engineering** ⚡:

   - Radare2 : unix-like reverse engineering framework
   - VirtusTotal : VirusTotal tools
   - Miasm : Reverse engineering framework
   - Mirror : reverses the bytes of a file
   - DnSpy : .NET debugger and assembly
   - AngrIo :  A python framework for analyzing binaries ( Suggested by @Hamz-a )
   - DLLRunner : a smart DLL execution script for malware analysis in sandbox systems.
   - Fuzzy Server : a Program That Uses Pre-Made Spike Scripts to Attack VulnServer.
   - yara : a tool aimed at helping malware researchers toidentify and classify malware samples
   - Spike : a protocol fuzzer creation kit + audits
   - other : other scripts collected somewhere

## **Exploitation** ❗:

   - Findsploit : Find exploits in local and online databases instantly
   - Pompem : Exploit and Vulnerability Finder
   - rfix : Python tool that helps RFI exploitation.
   - InUrlBr : Advanced search in search engines
   - Burpsuite : Burp Suite for security testing & scanning.
   - linux-exploit-suggester2 : Next-Generation Linux Kernel Exploit Suggester
   - other : other scripts I collected somewhere.

## **Shells** 🐚:

   - WebShells : BlackArch's Webshells Collection
   - ShellSum : A defense tool - detect web shells in local directories
   - Weevely : Weaponized web shell
   - python-pty-shells : Python PTY backdoors

## **Password Attacks** ✳️:
   - crunch : a wordlist generator
   - CeWL : a Custom Word List Generator
   - patator : a multi-purpose brute-forcer, with a modular design and a flexible usage

## **Encryption - Decryption** 🛡️:

   - Codetective : a tool to determine the crypto/encoding algorithm used
   - findmyhash : Python script to crack hashes using online services

## **Social Engineering** 🎭:

   - scythe : an accounts enumerator

# Lockdoor Resources contents 📚 :

## **Information Gathering** :mag_right: :
> - [Cheatsheet\_SMBEnumeration](ToolsResources/INFO-GATH/CHEATSHEETS/Cheatsheet_SMBEnumeration.txt)
> - [configuration\_management](ToolsResources/INFO-GATH/CHEATSHEETS/configuration_management.md)
> - [dns\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/dns_enumeration.md)
> - [file\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/file_enumeration.md)
> - [http\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/http_enumeration.md)
> - [information\_gathering\_owasp\_guide](ToolsResources/INFO-GATH/CHEATSHEETS/information_gathering_owasp_guide.md)
> - [miniserv\_webmin\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/miniserv_webmin_enumeration.md)
> - [ms\_sql\_server\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/ms_sql_server_enumeration.md)
> - [nfs\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/nfs_enumeration.md)
> - [osint\_recon\_ng](ToolsResources/INFO-GATH/CHEATSHEETS/osint_recon_ng.md)
> - [passive\_information\_gathering](ToolsResources/INFO-GATH/CHEATSHEETS/passive_information_gathering.md)
> - [pop3\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/pop3_enumeration.md)
> - [ports\_emumeration](ToolsResources/INFO-GATH/CHEATSHEETS/ports_emumeration.md)
> - [rpc\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/rpc_enumeration.md)
> - [scanning](ToolsResources/INFO-GATH/CHEATSHEETS/scanning.md)
> - [smb\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/smb_enumeration.md)
> - [smtp\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/smtp_enumeration.md)
> - [snmb\_enumeration](ToolsResources/INFO-GATH/CHEATSHEETS/snmb_enumeration.md)
> - [vulnerability\_scanning](ToolsResources/INFO-GATH/CHEATSHEETS/vulnerability_scanning.md)

## **Crypto** 🛡️:


> -   [Crypto101.pdf](ToolsResources/ENCRYPTION/CHEATSHEETS/Crypto101.pdf)

## **Exploitation** ❗:

> -   [computer\_network\_exploits](ToolsResources/EXPLOITATION/CHEATSHEETS/computer_network_exploits.md)
> -   [file\_inclusion\_vulnerabilities](ToolsResources/EXPLOITATION/CHEATSHEETS/file_inclusion_vulnerabilities.md)
> -   [File\_Transfers](ToolsResources/EXPLOITATION/CHEATSHEETS/File_Transfers.md)
> -   [nc\_transfers](ToolsResources/EXPLOITATION/CHEATSHEETS/nc_transfers.txt)
> -   [networking\_pivoting\_and\_tunneling](ToolsResources/EXPLOITATION/CHEATSHEETS/networking_pivoting_and_tunneling.md)
> -   [network\_pivoting\_techniques](ToolsResources/EXPLOITATION/CHEATSHEETS/network_pivoting_techniques.md)
> -   [pivoting](ToolsResources/EXPLOITATION/CHEATSHEETS/pivoting.md)
> -   [pivoting\_](ToolsResources/EXPLOITATION/CHEATSHEETS/pivoting_.md)
> -   [Public
>     Exploits](ToolsResources/EXPLOITATION/CHEATSHEETS/Public%20Exploits.md)
> -   [reverse\_shell\_with\_msfvenom](ToolsResources/EXPLOITATION/CHEATSHEETS/reverse_shell_with_msfvenom.md)

## **Networking** 🖧 :

> -   [bpf\_syntax](ToolsResources/NETWORKING/bpf_syntax.md)
> -   [Cheatsheet\_Networking](ToolsResources/NETWORKING/Cheatsheet_Networking.txt)
> -   [Cheatsheet\_Oracle](ToolsResources/NETWORKING/Cheatsheet_Oracle.txt)
> -   [networking\_concept](ToolsResources/NETWORKING/networking_concept.md)
> -   [nmap\_quick\_reference\_guide](ToolsResources/NETWORKING/nmap_quick_reference_guide.pdf)
> -   [tcpdump](ToolsResources/NETWORKING/tcpdump.pdf)

## **Password Attacks** ✳️:

> -   [password\_attacks](ToolsResources/PASSWORD/CHEATSHEETS/password_attacks.md)
> -   [Some-Links-To-Wordlists](ToolsResources/PASSWORD/CHEATSHEETS/Some-Links-To-Wordlists.txt)

## **Post Exploitation** ❗❗:

> -   [Cheatsheet\_AVBypass](ToolsResources/POST-EXPL/CHEATSHEETS/Cheatsheet_AVBypass.txt)
> -   [Cheatsheet\_BuildReviews](ToolsResources/POST-EXPL/CHEATSHEETS/Cheatsheet_BuildReviews.txt)
> -   [code-execution-reverse-shell-commands](ToolsResources/POST-EXPL/CHEATSHEETS/code-execution-reverse-shell-commands.txt)

## **Privilege Escalation** ⚠️:  
> - [Cheatsheet\_LinuxPrivilegeEsc](ToolsResources/PrivEsc/CHEATSHEETS/Cheatsheet_LinuxPrivilegeEsc.txt)
> - [linux\_enumeration](ToolsResources/PrivEsc/CHEATSHEETS/linux_enumeration.md)
> - [windows\_enumeration](ToolsResources/PrivEsc/CHEATSHEETS/windows_enumeration.md)
> - [windows\_priv\_escalation](ToolsResources/PrivEsc/CHEATSHEETS/windows_priv_escalation.md)
> - [windows\_priv\_escalation\_practical](ToolsResources/PrivEsc/CHEATSHEETS/windows_priv_escalation_practical.md)

## **Pentesting & Security Assessment Findings Report Templates** 📝 :
> - [Demo Company - Security Assessment Findings Report.docx](ToolsResources/REPORT/TEMPLATES/Demo-Company-Security-Asses-Findings-Report.docx)
> - [linux-template.md](ToolsResources/REPORT/TEMPLATES/linux-template.md)
> - [PWKv1-REPORT.doc](ToolsResources/REPORT/TEMPLATES/PWKv1-REPORT.doc)
> - [pwkv1\_report.doc](ToolsResources/REPORT/TEMPLATES/pwkv1_report.doc)
> - [template-penetration-testing-report-v03.pdf](ToolsResources/REPORT/TEMPLATES/template-penetration-testing-report-v03.pdf)
> - [windows-template.md](ToolsResources/REPORT/TEMPLATES/windows-template.md)
> - [OSCP-OS-XXXXX-Lab-Report\_Template3.2.docx](ToolsResources/REPORT/TEMPLATES/OSCP-OS-XXXXX-Lab-Report_Template3.2.docx)
> - [OSCP-OS-XXXXX-Exam-Report\_Template3.2.docx](ToolsResources/REPORT/TEMPLATES/OSCP-OS-XXXXX-Exam-Report_Template3.2.docx)
> - [CherryTree\_template.ctb](ToolsResources/REPORT/TEMPLATES/CherryTree_template.ctb)
> - [eventory-sample-pentest-report.pdf](ToolsResources/REPORT/TEMPLATES/eventory-sample-pentest-report.pdf)



## **Reverse Engineering** ⚡ : 
> - [Buffer\_Overflow\_Exploit](ToolsResources/REVERSE/CHEATSHEETS/Buffer_Overflow_Exploit.md)
> - [buffer\_overflows](ToolsResources/REVERSE/CHEATSHEETS/buffer_overflows.md)
> - [gdb\_cheat\_sheet](ToolsResources/REVERSE/CHEATSHEETS/gdb_cheat_sheet.pdf)
- [r2\_cheatsheet](ToolsResources/REVERSE/CHEATSHEETS/r2_cheatsheet.pdf)
> - [win32\_buffer\_overflow\_exploitation](ToolsResources/REVERSE/CHEATSHEETS/win32_buffer_overflow_exploitation.md)
> - [64\_ia\_32\_jmp\_instructions](ToolsResources/REVERSE/CHEATSHEETS/assembly/64_ia_32_jmp_instructions.pdf)
> - [course\_notes](ToolsResources/REVERSE/CHEATSHEETS/assembly/course_notes.md)
> - [debuging](ToolsResources/REVERSE/CHEATSHEETS/assembly/debuging.md)
> - [IntelCodeTable\_x86](ToolsResources/REVERSE/CHEATSHEETS/assembly/IntelCodeTable_x86.pdf)
> - [Radare2 cheatsheet](ToolsResources/REVERSE/CHEATSHEETS/assembly/Radare2%20cheat%20sheet.txt)
> - [x86\_assembly\_x86\_architecture](ToolsResources/REVERSE/CHEATSHEETS/assembly/x86_assembly_x86_architecture.pdf)
> - [x86\_opcode\_structure\_and\_instruction\_overview](ToolsResources/REVERSE/CHEATSHEETS/assembly/x86_opcode_structure_and_instruction_overview.png)

## **Social Engineering** 🎭:

> -   [social\_engineering](ToolsResources/SOCIAL_ENGINEERING/CHEATSHEETS/social_engineering.md)

## **Walk Throughs** 🚶 :

> -   [Cheatsheet\_PenTesting.txt](ToolsResources/WALK/Cheatsheet_PenTesting.txt)
> -   [OWASP Testing Guide v4](ToolsResources/WALK/OTGv4.pdf)
> -   [OWASPv4\_Checklist.xlsx](ToolsResources/WALK/OWASPv4_Checklist.xlsx)

## **Web Hacking** 🌐 :

> -   [auxiliary\_info.md](ToolsResources/WEB/CHEATSHEETS/auxiliary_info.md)
> -   [Cheatsheet\_ApacheSSL](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_ApacheSSL.txt)
> -   [Cheatsheet\_AttackingMSSQL](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_AttackingMSSQL.txt)
> -   [Cheatsheet\_DomainAdminExploitation](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_DomainAdminExploitation.txt)
> -   [Cheatsheet\_SQLInjection](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_SQLInjection.txt)
> -   [Cheatsheet\_VulnVerify.txt](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_VulnVerify.txt)
> -   [code-execution-reverse-shell-commands](ToolsResources/WEB/CHEATSHEETS/code-execution-reverse-shell-commands.txt)
> -   [file\_upload.md](ToolsResources/WEB/CHEATSHEETS/file_upload.md)
> -   [html5\_cheat\_sheet](ToolsResources/WEB/CHEATSHEETS/html5_cheat_sheet.pdf)
> -   [jquery\_cheat\_sheet\_1.3.2](ToolsResources/WEB/CHEATSHEETS/jquery_cheat_sheet_1.3.2.pdf)
> -   [sqli](ToolsResources/WEB/CHEATSHEETS/sqli.md)
> -   [sqli\_cheatsheet](ToolsResources/WEB/CHEATSHEETS/sqli_cheatsheet.md)
> -   [sqli-quries](ToolsResources/WEB/CHEATSHEETS/sqli-quries.txt)
> -   [sqli-tips](ToolsResources/WEB/CHEATSHEETS/sqli-tips.txt)
> -   [web\_app\_security](ToolsResources/WEB/CHEATSHEETS/web_app_security.md)
> -   [web\_app\_vulns\_Arabic](ToolsResources/WEB/CHEATSHEETS/web_app_vulns_Arabic.md)
> -   [Xss\_1](ToolsResources/WEB/CHEATSHEETS/xss.md)
> -   [Xss\_2](ToolsResources/WEB/CHEATSHEETS/xss.png)
> -   [xss\_actionscript](ToolsResources/WEB/CHEATSHEETS/xss_actionscript)
> -   [xxe](ToolsResources/WEB/CHEATSHEETS/xxe.md)

## **Other** 📚 :

> - [Best collection Ever](https://collection.sofianehamlaoui.fr)  
>
> -   [Images (I'll let you discover that)](ToolsResources/IMAGES/)
> -   [Google Hacking DataBase](ToolsResources/GHDB.pdf)
> -   [Google Fu](ToolsResources/GoogleFu.pdf)
