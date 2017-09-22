# R558U Clover and  Kext Files For Mac Installation

# Device Specification
  
  CPU:      Corei5-6200U up to 2.8GHz
  
  Audio:    ALC255
  
  Wifi:     Realtek 8723be
  
  Trackpad: ELAN1000 touchpad

# Before Installation

1) Mount EFI partition of Mac Installer

2) Copy and replace clover files

3) replace Clover/ACPI/patched/DSDT.aml with DSDT/Final_DSDT/DSDT.aml

(*Warning: only copy and place DSDT.aml do not copy any other files inside that folder)

# After Installation

1)  Flash all the kext files using kext utility
  
2)  Trackpad(VoodooI2C):  To Enable Trackpad, Remove all the LPSS oriented Kext files inside '/System/Library/Extensions'

3)  Audio(AppleALC):       If you want External Mic to work, you have to route the External mic using this guide:  http://forum.osxlatitude.com/index.php?/topic/1946-complete-applehda-patching-guide/
   
   *Note: Wifi and Internal Mic Doesn't Work
