# dell-precision-t1700-opencore-big-sur
OpenCore EFI files and kexts for a Dell Precision T1700 running a Haswell CPU (Intel Core 4XXX)

![neofetch](https://github.com/cube-builder/dell-precision-t1700-opencore-big-sur/blob/main/Screen%20Shot%202021-08-18%20at%2010.30.32%20PM.png?raw=true)

OpenCore EFI and kexts files for a Dell Precision T1700 for macOS 11.5.2
<br>
**UPDATE 1/25/2023**: I tested this with Monterey and it seems to work fine and haven't noticed any issues but I haven't gone much further into seeing what issues it had. 
<br>
For Catalina you can view the other repo <a href="https://github.com/cube-builder/dell-precision-t1700-opencore-catalina">here</a>
<br>
This **should** work on your Precision T1700 system running a Haswell CPU. To check if your computer is Haswell just make sure it begins with Intel Core iX 4XXX and this will probably work for your system.

### Note
Audio may not work if you're using the bulit in audio this is because I use headphones or external speakers on my system due to the internal speakers being very terrible which is why I did not set it up

WiFi is not setup either since I use Ethernet on my system and this computer doesn't come with WiFI if you want to use Wifi you can follow the opencore guide <a href="https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth">here</a> to get it working. 

Recovery is not included either to install the OS so you **should** already have the recovery files which can also be followed in the OpenCore guide.

This **might** work on Dell Optiplexes that have haswell CPUs too.

### My Specs
CPU: Intel Core i7-4790 (also using intergrated GPU)
<br>
Ram: 16GB DDR3
<br>
Storage: 256GB Micron SSD


### BIOS Settings
To boot on the BIOS on your Precision press F2 while turning on the computer then do the following:

Go to SATA operation and change it to AHCI mode
<br>
Turn on UEFI and turn off legacy rom and secure boot.

