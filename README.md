## EFI-Intel-i3-10100-MSI-H410M-A-PRO-Hackintosh-Opencore-1.02

*   Working EFI Folder for Intel Core i3-10100 and MSI H410-M-A Pro
    
*   Opencore v1.02 - Kexts updated 11/2024
    
*   MacOS 12 Monterey working (Ventura/Sonoma not tested yet)
    

**Dortania Guide:**

*   [https://dortania.github.io/OpenCore-Install-Guide/](https://dortania.github.io/OpenCore-Install-Guide/)
    


**Download Opencore 1.0.2-RELEASE here:**

*	[https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.2/](https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.2/)



go to OpenCore-1.0.2-RELEASE\Utilities\macrecovery  
open CMD and download Monterey recovery

```javascript
py macrecovery.py -b Mac-FFE5EF870D7BA81A -m 00000000000000000 download
```