## EFI-Intel-i3-10100-MSI-H410M-A-PRO-Hackintosh-Opencore-1.02

*   Working EFI Folder for Intel Core i3-10100 and MSI H410-M-A Pro
    
*   Opencore v1.02 - Kexts updated 11/2024
    
*   MacOS 12 Monterey working (Ventura/Sonoma not tested yet)
    

**Dortania Guide:**

*   [https://dortania.github.io/OpenCore-Install-Guide/](https://dortania.github.io/OpenCore-Install-Guide/)
    


**Download Opencore 1.0.2-RELEASE here:**

*	[https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.2/](https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.2/)




*	go to OpenCore-1.0.2-RELEASE\Utilities\macrecovery  
*	then open CMD in that directory and download Monterey recovery with following command:

```javascript
py macrecovery.py -b Mac-FFE5EF870D7BA81A -m 00000000000000000 download
```

*    create a new folder named "com.apple.recovery.boot" and copy the downloaded files (BaseSystem.dmg and BaseSystem.chunklist) into that folder.
  
*    go to [https://dortania.github.io/OpenCore-Install-Guide/installer-guide/](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) an follow the guide to create the USB installer 
