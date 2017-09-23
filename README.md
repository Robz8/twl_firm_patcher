# twl_firm_patcher

This patcher that allows to produce a special twlBg.cxi by patching the devLauncher SRL contained into it.

Python 2.7 and devKitPro (msys) are required and needs to be available in the Path.

This modifed twlBg.cxi allows to redirect DSiWare to SD.

Please note that the DSiWare CIA needs to be installed to the system, but without the NitroFS data.

Usage :
- Dump the twl_firm of your console using decrypt9 (SysNAND Options->Miscellanous->NCCH FIRMs Dump)
- rename it to firmware_twl.bin and put it into input.
- run go.cmd (o3ds or n3ds, depending on your console)
- put the twlBg.cxi file into luma/sysmodules (V6.0 dev version required)
- an "enabler" program is needed to unlock the HW.

Thanks to Nocash and Steveice10 for their reverse engineering work and the documentation produced.
 