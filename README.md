# R558U Clover, CustomPatched DSDT and  Kext Files For Hackintosh

# Device Specification
  
  CPU:      Corei5-6200U up to 2.8GHz
  
  Audio:    ALC255
  
  Wifi:     Realtek 8723be
  
  Trackpad: ELAN1000 touchpad

# Before Installation

1) Mount EFI partition of Mac Installer

2) Copy and replace clover files

3) replace Clover/ACPI/patched/DSDT.aml with DSDT/Final_DSDT/DSDT.aml

(*Warning: do not copy any *.asl files inside that folder)

# After Installation

1)  Flash all the kext files using kext utility
  
2)  Trackpad(VoodooI2C):  To Enable Trackpad, Remove all the LPSS oriented Kext files inside '/System/Library/Extensions'

3)  Audio(AppleALC):       If you want External Mic to work, you have to route the External mic using this guide:  http://forum.osxlatitude.com/index.php?/topic/1946-complete-applehda-patching-guide/
   
   Not Working:
             Wifi,
             Card reader and
             LineIn Mic
             
            
High sierra Updated : Disable NVidia Optimus Detection permenantly in DSDT (so it save some power and boot without a problem
