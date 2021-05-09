# Few useful linux commands:

`nproc` - print the number of processing units available.

`ls -ltrh` - list files using:  
- l -long listing 
- t - sort by time; newest first  
- r - reverse sorting  
- h - human-readable

`sudo dmidecode` - DMI(Desktop Management Interface) table decoder.  

- dmidecode command is used when the user want to retrieve system’s hardware related information such as Processor, RAM(DIMMs), BIOS detail, Memory, Serial numbers etc. of Linux system in a readable format.
- Eg:
    - `sudo dmidecode |grep Version`
    - `sudo dmidecode | grep -A 9 "System Information"`
    
