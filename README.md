
# Laptop Information Check

## 1. System Information Check (e.g., Born Date, Manufacture Date, Serial Number etc.) and check Serial number in online.
     
    Action: BIOS (e.g., ESC Key -> F12)
     
## 2. CPU + Max RAM Slot + HDD Check + Graphics Card

    Action: Task Manager (e.g., Task Manager -> Performace)
    
# 3. Check Serial Number and validated its expire date via online (e.g., https://support.hp.com)
 
    Action: CMD : wmic bios get serialnumber (e.g., WinKey+R -> CMD -> wmic bios get serialnumber)

# 4. Battery Checkup
    
    Action: CMD : powercfg /batteryreport (e.g., WinKey+R -> CMD -> powercfg /batteryreport)
    
# 5. Didplay Checkup
    
    Action: Open a browser then visit : https://www.eizo.be/monitor-test (Online software)
    
# 6. Sound Checkup

    Action: Control panel -> Sound configuration (Left Right speaker)
    
# 7. Keyboad Checkup: 
    
    Action: Open a browser and visit : https://www.keyboardtester.com/tester.html (Online software) 
    
# 8. Camera, Internet (Wifi + LAN)
    
    Action: Control Panel 

# 9. Overall Hardware Check 

    Action: CMD : dmidecode 
    
    Steps: 
    
    DmiDecode for Windows (http://www.techian.com/windows/dmidecode-for-windows/)
    Download DmiDecode Install it, then you have to set the path open a command line window and type

    path=C:\Program Files\GnuWin32\sbin

    If it is installed in C:\Program Files\  then the biosdecode prints all BIOS related information it can find.

    Now you can execute commands

    dmidecode –t x where x can be

    0 – BIOS 
    1 – System 
    2 – Base Board 
    3 – Chassis 
    4 – Processor 
    5 – Memory Controller 
    6 – Memory Module 
    7 – Cache 
    8 – Port Connector 
    9 – System Slots 
    10 – OnBoard Devices 
    11 – OEMStrings 
    12 – SystemConfiguration Options
 
 That's it. 
