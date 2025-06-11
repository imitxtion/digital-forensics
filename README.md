# Digital Forensics
My write-ups from solving assignments in the Digital Forensics course at TU Wien.

## Assignment 1: Veracrypt
This project involved recovering a password from a VeraCrypt container using a GPU-accelerated brute-force attack with Hashcat. Password was successfully cracked, allowing access to the container's contents, which included image files and a text file with a hash value.

The investigation also included an analysis of how password length and complexity affect brute-force cracking times. Based on this, recommendations were formulated for creating strong password to ensure long-term security against such attacks. 

## Assignment 2: File Systems Forensics
This project involved investigating a qcow disk image from a Windows 7 system to examine potential intellectual property theft.

The system was booted using VirtualBox, and Autopsy was employed for in-depth analysis, including file carving and recovering deleted files. This process uncovered user accounts and relevant files in public directories. Critical artifacts such as user profiles, browser history, and email communications were recovered.

The investigation successfully identified email correspondence that confirmed an employee leaked a sensitive character design file to another individual involved in the case. Additionally, an unrelated TeslaCrypt ransomware infection was discovered on the system through emails and a ransom note.

## Assignment 3: RAM Forensics
This project involved comprehensive memory forensics, encompassing both RAM acquisition and detailed RAM analysis. I utilized WinPMem to capture a RAM dump from a Windows 10 virtual machine. Subsequently, Volatility 3 was employed to analyze this acquired memory, along with a provided RAM dump. The analysis focused on identifying critical system information, including operating system details, active processes, network connections, and user details. This assignment demonstrated proficiency in interpreting volatile memory data for digital investigations.

## Assignment 4: Smartphone
This project focused on memory forensics, encompassing both RAM acquisition and comprehensive RAM analysis.
The RAM acquisition task involved capturing a memory dump from a Windows 10 virtual machine using WinPMem. The subsequent RAM analysis utilized Volatility 3 to examine both the acquired dump and a provided RAM dump.

Key investigative steps included:
- Analyzing operating system details and system timestamps
- Listing and scanning active processes to identify running applications
- Examining network connections and activities
- Identifying user details, including the user SID and attempting to retrieve the user password hash
