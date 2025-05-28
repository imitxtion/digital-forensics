# Digital Forensics
My write-ups from solving assignments in the Digital Forensics course at TU Wien.

## Assignment 1: Veracrypt
This project involved recovering a password from a VeraCrypt container using a GPU-accelerated brute-force attack with Hashcat. Password was successfully cracked, allowing access to the container's contents, which included image files and a text file with a hash value.

The investigation also included an analysis of how password length and complexity affect brute-force cracking times. Based on this, recommendations were formulated for creating strong password to ensure long-term security against such attacks. 

## Assignment 2: File Systems
This project involved investigating a qcow disk image from a Windows 7 system to examine potential intellectual property theft.

The system was booted using VirtualBox, and Autopsy was employed for in-depth analysis, including file carving and recovering deleted files. This process uncovered user accounts and relevant files in public directories. Critical artifacts such as user profiles, browser history, and email communications were recovered.

The investigation successfully identified email correspondence that confirmed an employee leaked a sensitive character design file to another individual involved in the case. Additionally, an unrelated TeslaCrypt ransomware infection was discovered on the system through emails and a ransom note.

## Assignment 3: RAM
In progress...
