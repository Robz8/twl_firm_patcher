# twl_firm_patcher

This patcher that allows to produce a special twlBg.cxi by patching the devLauncher SRL contained into it.

Python 2.7 and devKitPro (msys) are required and needs to be available in the Path.

This modifed twlBg.cxi allows to redirect DSiWare to SD.

Please note that the DSiWare CIA needs to be installed to the system. It is recommended to exclude the NitroFS data from the .nds file before making CIA.

Usage :
- Dump the twl_firm of your console using decrypt9 (SysNAND Options->Miscellanous->NCCH FIRMs Dump)
- rename it to firmware_twl.bin and put it into input.
- run go.cmd (o3ds or n3ds, depending on your console)
- put the twlBg.cxi file into luma/sysmodules
- Enable "loading external FIRMs and modules" in Luma settings

Thanks to Nocash and Steveice10 for their reverse engineering work and the documentation produced.
 