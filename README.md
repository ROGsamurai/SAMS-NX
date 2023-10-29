This pack includes several components, which is the latest version of Hekate, Atmosphere and Signature patches  and some payloads like the latest version of Lockpick_RCM, and Tegraexplorer along with its Scripts.

## HOW TO INSTALL THE PACK

Watch this : https://www.youtube.com/watch?v=jfJIVzeJSyE

1. Delete the existing Atmosphere, Config , Bootloader, Sept folder from your SD card
2. Extract the HATS pack to your SD card
3. Inject the SX Loader Payload for unpatched Switch or just boot the console for all patched Switch including the Lites
4. You will then boot to Hekate. Press launch and choose whatever environment you are going to load.


## HOW TO UPDATE THE PACK AND UPDATE THE FIRMWARE
[![HATS AMS UPDATE](https://i3.ytimg.com/vi/4jw4nyymWgc/maxresdefault.jpg)](https://www.youtube.com/watch?v=4jw4nyymWgc)

- Please watch this guide : https://youtu.be/4jw4nyymWgc?si=VVgpM0ILa0C3O4f-

## HOW TO UPDATE THE CONSOLE FIRMWARE
[![DAYBREAK](https://i3.ytimg.com/vi/W_OjR-yxfdY/maxresdefault.jpg)](https://www.youtube.com/watch?v=4jw4nyymWgc)
- Please watch this video https://youtu.be/W_OjR-yxfdY

## HOW TO SETUP THE SD CARD FROM SCRATCH
[![SETUP FROM SCRATCH](https://i3.ytimg.com/vi/up_sjzKHFeU/maxresdefault.jpg)](https://www.youtube.com/watch?v=up_sjzKHFeU)
Please watch this guide : https://youtu.be/up_sjzKHFeU?si=Bb9yey67KynnEq4R

## ABSOLUTE LINK

Use this link to always download the updated pack
https://link.sthetix.info/hats


## WHY IS IT CALLED SAMS-NX ?

Well, it means (S)Switch, (A)AND, (M)Mods, (S)Stuff - (NX)Instinct v6

## WHAT IS SYSMMC / EMUMMC / STOCK

- STOCK is OFW. It is the actual factory firmware that comes from the factory
- SYSMMC is OFW with patches or CFW. You can run homebrews on it but do not install game backups on this world unless you know what you are doing and its consequences. It reflects the OFW/STOCK itself. 
- EMUMMC is the emulated SYSMMC. It copied itself from the OFW and placed inside the micro SD card, and it is always in the CFW method. It is unrelated to the STOCK/OFW/SYSMMC as it is a different entity after creation. You can install and run anything here, like game backups, homebrews, etc. 

## HOW TO USE THE PACK WISELY AND NOT GET BANNED

- Do not install game backups or run Tinfoil on the SYSMMC, as it reflects the OFW. If you accidentally installed those stuff, please do the SYSTEMWIPE immediately: https://youtu.be/n6xEakq3n58
- Install game backups and others under the EMUMMC mode
- You can connect the SYSMMC and the EMUMMC to the internet as the exosphere.ini hides the console's serial number on all CFW modes
- To connect the SYSMMC to the e-shop or the Big N server, you must edit the exosphere.ini file and alter the blank_prodinfo_sysmmc=1 to blank_prodinfo_sysmmc=0. Make sure you know what you are doing and know the consequences of doing this.
- Do not use cheats on online games (like the splatoon 3)


## HOW TO BOOT TO ANY CFW MODE FROM HEKATE

To boot to any CFW mode, please follow this guide.

![cfw](https://github.com/sthetix/HATS/blob/main/cfw.png)

## HOW TO BOOT TO THE REAL STOCK (OFW) FROM HEKATE

To boot to real stock, please follow this guide 
because launching OFW from the Launch menu is NOT the real stock, but semi-stock as stated here https://github.com/CTCaer/hekate/blob/master/res/hekate_ipl_template.ini

![stock](https://github.com/sthetix/HATS/blob/main/stock.png)

## HOW TO TRANSFER FILES INTO/FROM YOUR CONSOLE TO YOUR COMPUTER WIRELESSLY

1. Make sure you have connected your console to your home network
2. Open the album
3. Press Y  to find the IP address of your console
4. Open any FTP manager on your computer
5. Connect to the IP address shown on your console on port 5000 with username/password: switch/switch

## HOW TO INSTALL THE GAMES
[![DBI MTP](https://i3.ytimg.com/vi/SEvtKeoIqS8/maxresdefault.jpg)](https://www.youtube.com/watch?v=SEvtKeoIqS8)
To install the games, please watch this guide : https://youtu.be/SEvtKeoIqS8?si=7ZDBNMKPS6S_goTy


## HOW TO TRANSFER GAME SAVE DATA TO ANOTHER CONSOLE / HOS
[![TRANSFER SAVE DATA](https://i3.ytimg.com/vi/HoyvuH2GU0Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=HoyvuH2GU0Q)
To do it, please watch this guide :https://youtu.be/HoyvuH2GU0Q?si=sAfQ_Q2axEvs1PuD


## HOW TO UPGRADE THE SD CARD
[![UPGRADE THE SD CARD](https://i3.ytimg.com/vi/FnDsm18jQsM/maxresdefault.jpg)](https://www.youtube.com/watch?v=FnDsm18jQsM)
To upgrade the current SD card to a new one, please watch this guide : https://youtu.be/FnDsm18jQsM?si=knTP8D5uA6WIZQTv


## ERROR 2023-0011 , 2137-8007 , 2155-8007  SOLUTION
![2023-0011](https://github.com/sthetix/HATS/blob/main/2023-0011.png)
![2137-8007](https://github.com/sthetix/HATS/blob/main/2137-8007.jpg)
![2155-8007](https://github.com/sthetix/HATS/blob/main/2155-8007.jpg)

The HATS pack hides the console's serial number on all CFW modes and blocks all Nintendo servers with DNS Mitm method. That is why if you launched the sysMMC or the emuMMC and tried to connect the console to eshop or update the games online or try to log-in, you will see this error code.
To solve this issue, please boot to the OFW mode https://github.com/sthetix/HATS#how-to-boot-to-the-real-stock-ofw-from-hekate


## HOW TO CONNECT THE CONSOLE TO THE NINTENDO SERVER WHILE RUNNING THE CFW MODE

As mentioned, the HATS pack hides the console's serial number on all CFW modes and DNS Mitm method to prevent your console from getting banned online if you accidentally / unintentionally installed pirated or illegal apps/games.
However, to connect the CFW modes to the Nintendo server, you must edit the exosphere.ini at the root of the SD card with a notepad. Use this guide responsibly as it will expose your console for a possible ban.

To connect the sysMMC to the Nintendo server, please edit

*blank_prodinfo_sysmmc=1* to *blank_prodinfo_sysmmc=0*

To connect the emuMMC to the Nintendo server, please edit

*blank_prodinfo_emummc=1* to *blank_prodinfo_emummc=0*

![edit-exosphere](https://github.com/sthetix/HATS/blob/main/edit-exosphere.gif)


To disable the DNS Mitm protection, please open the system_settings.ini file inside the Atmosphere/Config folder and comment out these lines : (add ; in front of the line) 

*enable_dns_mitm = u8!0x1* to *; enable_dns_mitm = u8!0x1*

*add_defaults_to_dns_hosts = u8!0x1* to *; add_defaults_to_dns_hosts = u8!0x1*

![edit-lines-dns](https://github.com/sthetix/HATS/blob/main/edit-lines-dns.gif)

## HOW TO CREATE YOUR OWN HATS PACK

1. Download the latest Atmosphere from https://github.com/Atmosphere-NX/Atmosphere/releases
2. Download the latest Hekate from https://github.com/CTCaer/hekate/releases
3. Download the latest signature patches from https://sigmapatches.coomer.party/
4. Download the latest Tinfoil from Tinfoil.io
5. Download the latest DBI from https://github.com/rashevskyv/dbi/releases
6. Download the SX Gear boot.dat and boot.ini from https://u.pcloud.link/publink/show?code=XZCMlYXZNIJUnyr352XVWoXCuPo2SmwsRGpk
7. Download the hekate_ipl.ini and its graphic resource from: https://u.pcloud.link/publink/show?code=XZAkVUXZkgrREaCGTQLsTYfCeUqXFhKDnfBk
8. Create the DBI folder inside the Switch folder and put the latest DBI into it (the .nro and its .config)
9. Download any tools/homebrew apps you want to add to the pack
10. Combine them all together, like extract them all into a folder, put the payloads file inside the bootloader folder








## CREDIT

[CTCaer](https://github.com/CTCaer)
[Atmosphere-NX](https://github.com/Atmosphere-NX)
[Blawar](https://github.com/blawar)
[ITotalJustice](https://github.com/ITotalJustice)
[suchmememanyskill](https://github.com/suchmememanyskill)
[shchmue](https://github.com/shchmue)
[rashevskyv](https://github.com/rashevskyv)
[fortheusers](https://github.com/fortheusers)
[Werwolv](https://github.com/WerWolv)
[carcaschoi](https://github.com/carcaschoi)
[HamletDuFromage](https://github.com/HamletDuFromage)
[dezem](https://github.com/dezem)
[hwfly-nx](https://github.com/hwfly-nx)
[cathery](https://github.com/cathery)
[jits](https://jits.cc)
[titz](https://titz.cf)
[stealtshop](https://stealthshop.cf)
[quotanx](https://quotanx.in)
[pengu](https://pengu.us)
[teknik](https://teknik.app)
[DarkMatterCore](https://github.com/DarkMatterCore)
[J-D-K](https://github.com/J-D-K)
[tomvita](https://github.com/tomvita)
[proferabg](https://github.com/proferabg)
[masagrator](https://github.com/masagrator)
[SunResearchInstitute](https://github.com/SunResearchInstitute)
[SegFault42](https://github.com/SegFault42)
[mtheall](https://github.com/mtheall)
[joel16](https://github.com/joel16)
[XorTroll](https://github.com/XorTroll)
[proferabg](https://github.com/proferabg)
[rdmrocha](https://github.com/rdmrocha)
