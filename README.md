# R558U Clover and  Kext Files For Mac Installation

# Device Specification
  
  CPU:      Corei5-6200U up to 2.8GHz
  
  Audio:    ALC255
  
  Wifi:     Realtek 8723be
  
  Trackpad: ELAN1000 touchpad

# Before Installation

1) Mount EFI partition of Mac Installer

2) Copy and replace clover files

# After Installation

 Flash all the kext files using kext utility
  
Trackpad(VoodooI2C):
        To Enable Trackpad, Remove all the LPSS oriented Kext files inside '/System/Library/Extensions'

Audio(AppleALC):
        If you want External Mic to work, you have to route the External mic using this guide:  http://forum.osxlatitude.com/index.php?/topic/1946-complete-applehda-patching-guide/
   
   *Note: Wifi and External Mic Doesn't Work
