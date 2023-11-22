
# EnragedRabbitProject

Welcome to the Enraged Rabbit Project Github page!

This project aims to bring multimaterial capabilities to 3D printers using a single Direct Drive toolhead. While this project is mainly dedicated to be used on VORON printers, it can also be used (or adapted) on any 3D printer that runs Klipper, and potentially RRF.

## Table of Content
- [Changelog](#changelog)
- [Showroom](#showroom)
- [Videos](#videos)
- [Details](#details)
- [BOM](#bom)
- [Acknowledgements](#acknowledgements)
- [FAQ](https://github.com/EtteGit/EnragedRabbitProject/tree/main/Documentation/FAQ)
- [Carrot Patch](https://github.com/EtteGit/EnragedRabbitProject/blob/main/Documentation/FAQ/FAQ_ERCP.md)
- [Carrot Feeder](https://github.com/EtteGit/EnragedRabbitProject/blob/main/Documentation/FAQ/FAQ_ERCF.md)
 
## Changelog
- **November 22th 2023 :** Started.

## Showroom

<img src="Showroom/Spidermans.png" alt="Spidermans" width="950"/><img src="Showroom/NoS_Prints.png" alt="NoS_prints" width="950"/><img src="Showroom/BnE_Prints.png" alt="BnE_Prints" width="950"/><img src=Showroom/Bimaterial_logo.png alt="Voron Logo TPU" width="650"/><img src=Showroom/9_colors_test.png alt="9_colors_test" width="400"/>

## Videos
Here are videos of the system in action. I need to release more videos...

https://streamable.com/3lo192

https://streamable.com/cjl2iz

## Details

There are 4 components so far : 
 - **The Enraged Rabbit Carrot Feeder (ERCF)**. The Carrot Feeder allows to use a high number of different filaments (tested up to 9 channels so far) and feed them, one at a time, into the printer toolhead. The ERCF gear motion system (i.e. what is used to push and pull the filament) is based on the Voron Design M4 extruder. The ERCF was inspired by the Prusa MMU2 and the Smuff.

  <img src="https://cdn.discordapp.com/attachments/842792223769624605/888344547501940736/20210917_103629.jpg" alt="Carrot Feeder" width="600"/><img src="https://cdn.discordapp.com/attachments/842792223769624605/888344548298874880/20210917_103640.jpg" alt="Carrot Feeder 2" width="600"/>
 
 - **The Enraged Rabbit Carrot Patch (ERCP)**. It is a light spool-holder and buffer combo to help you deal with the filament  
management issue associated with multimaterial systems.
 
 <img src="https://cdn.discordapp.com/attachments/788818216260337664/807282522756350022/image0.jpg" alt="Carrot Patch" width="300"/><img src="https://cdn.discordapp.com/attachments/500407802414628876/806108474668613632/20210202_112459.jpg" alt="Carrot Patch 2" width="300"/>
 - **The Enraged Rabbit King's Seat (ERKS)**. The King’s Seat is a pellet-purge system to remove the need for a wipe-tower and make faster filament purges. This system is designed for Voron V2s only so far.
 - **The filament sensor** : a filament sensor system located below the extruder gears to check proper loading and unloading of filament.
  
Note that this is a work in progress !!
 
Only the King's Seat is yet to be released !
 
## BOM
 The BOM for those components can be found [here](https://docs.google.com/spreadsheets/d/1A_qeNeaVprh_iPbvLcLjvJ2o2NfCzjuJam3K3RkWW0w).
 
## Acknowledgements

Thanks to the VORON Design devs and VORON discord members for the discussions and support, with a special thanks to the #honhonhonbaguette-FR members and @Tircown#8715!!

Thanks to Fabreeko, DeepFriedHero (DFH), Blurolls and many others for supporting this project!

Ette
