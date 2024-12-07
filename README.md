# HWID Spoofer for Windows  

**A Hardware ID Spoofer for Windows systems.**  

### Overview  
This tool is designed to spoof hardware identifiers on Windows. It has been tested on the following versions:  
- **Windows 10 x64**:  
  - 1507 (10240)  
  - 1809 (17763.379)  
  - 1903 (18362.30 and 18362.175)  

While it may provide some functionality on lower versions of Windows, these have not been tested.  

### Features  
#### Driver Capabilities:  
- Spoofs identifiers for:  
  - Disk  
  - Volume  
  - NIC (+ ARP)  
  - SMBIOS  
  - Boot  
  - GPU  

#### Usermode Program:  
- Handles:  
  - Registry keys  
  - Common tracking files  

### Limitations  
- **IP, SIDs, and AC/game-specific files**: These can still be used to identify you.  
- **NVME-specific IOCTLs**: Not handled.  
- **VPN Usage**: Load the driver **after** the VPN's TAP driver is loaded to ensure proper functionality.  

### Important Notes  
- This project has been **archived**.  
- It serves as an example of handling common queries, but much of the code was written hastily.  
- **No future support will be provided.**  

### Disclaimer  
This software is for **educational and privacy purposes only**. The creator does not endorse misuse, such as bypassing bans or violating terms of service. Use responsibly.  
