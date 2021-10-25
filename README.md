Instruction:
1. Go to setting then about phone  and click BUILD 7 times until it says developers mode
https://youtu.be/QgtMTUgLWmI?t=10

2. Put your device into fastboot  mode by turning off your device, then holding volume down + power wait for the buzz
how to fastboot https://youtu.be/0MPv_hSH3hk?t=134

3. Download and Run 
https://drive.google.com/file/d/0B0MK...
Its the 15-second adb installer.  See forum for details.
https://forum.xda-developers.com/t/of...
Connect your comma two (via a USB-C to USB-A cable) or EON Gold (via a USB-mini-B to USB-A cable) to your computer

4 Download and unzip  platform tools
make sure to unzip to a folder named   "platform-tools" https://cdn.discordapp.com/attachment...
https://developer.android.com/studio/...

5.  go to folder platform tools 
then shift +right click powershell
https://cdn.discordapp.com/attachment...

6. Run            ./fastboot oem unlock-go
 https://cdn.discordapp.com/attachment...

7. Once unlock
 Goto https://github.com/commaai/eon-neos
Download and unzip   to eon-neos-master folder
https://cdn.discordapp.com/attachment...

8. Download & install Python  https://www.python.org/downloads/rele...

9. Copy platform tools folder and paste it inside  eon-neos-master folder
https://cdn.discordapp.com/attachment...

10 . While inside  eon-neos-master  folder shift + right click then open powershell


11. Run download.py  by typing             python download.py 
     it will take a while since its downloading the neos image etc.
https://cdn.discordapp.com/attachment...

12. To Allow scripts  copy and paste 

Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

https://cdn.discordapp.com/attachment...

13.  Run flash.ps1  by typing                 ./flash.ps1

https://cdn.discordapp.com/attachment...

************************************************************************
DO NOT DISCONNECT THE DEVICE! YOU WILL BRICK YOUR PHONE
**********************************************************************

https://www.youtube.com/watch?v=7AnygDRdT4U
