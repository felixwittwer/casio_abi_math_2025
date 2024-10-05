[![Generic badge](https://img.shields.io/badge/newest_version-2024.1.2-<COLOR>.svg)](https://github.com/felixwittwer/casio_abi_math_2025/releases)
[![Static Badge](https://img.shields.io/badge/project_from_students_at-Gymnasium_Dresden--Plauen-GDP?color=055d3d)](https://gdp.schule/)
[![Static Badge](https://img.shields.io/badge/development_for-Abitur_2025-GDP?color=ff2000)]()

# casio_abi_math_2025
a collection of programs designed to assist in any field of mathematics needed to pass the German A-levels in Saxony

## LICENSE
This work is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

[![licensebuttons by-nc-sa](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)

## THANKS
to **Charlotte Bäcker** for the original projekt and permission to reuse and further develop it

to **Felix Wittwer** for giving the orginial ABI 2017 program a new life

## CONTACT
Felix Wittwer (felix.wittwer.mail@gmail.com)

<div id=compatibility>
  
## Compatibility
Supported calculators:
Casio fx-9860 GII
Casio fx-9860 GII SD
Casio fx-9860 GIII
Casio fx-CG50

</div>


## Versions | Changelog
#### naming convention 
year . main version (for major changes) . sub version (for small changes of bug fixes)

### 2024.1.1
- add probability for "höchstens eine Standardabweichung" (fix issue #14) 
- "Binomial" menu is referencing "Ebenen" menu (fix issue #15)
- "Statistik" menu incorectly labled as "Ebenen" (fix issue #16)
- make "Vierfeldertafel" more logical (fix issue #18)
- show input directly in "Vierfeldertafel" (fix issue #19)
- add support for Casio fx-CG50 (fix issue #20)
- minimize confusion when asked for probability input (fix issue #21)

### 2024.1.0
- spliting the Program into 9 different files for better readability and to reduce confusion with variable names
- rename a lot of varibales
- brining UX changes (mostly putting "Zurück" at the top of every menu)
- new more logical menu structure
- order menu numbers and letters in Code to get rid of confusion (main menu's 1 to 9, submenus A to Z)
- add Variablenmanager (save and restore the values you allocated to some Varibales)
- add new "Vektor" menu with "Vektor aus Pnkte", "Pnkte aus Vektor", "Vektorlänge", "Lineare Abhängig", "Einheitsvektor" and "Dreiecksfläche"
- add new "Geraden" menu with "Gerade aus Pnkte", "Pnkte aus Gerade" (old menu functionality regarding Geraden was also moved to this menu)
- add new functionality inside "Kurvendiskussion" menu ("Sattelpunkte", "Intervall ändern")

all changes made by Felix Wittwer

### 2017.1.0 
- origianl version by Charlotte Bäcker


## Installation
### via USB
#### fx-9860 GII
1. [Download](https://edu.casio.com/dl/) and install the Casio FA-124 Programm

Due to the complexety of the program I won't explain every detail in this README. For further information use the [official manual (German)](https://support.casio.com/storage/de/manual/pdf/DE/004/FA-124_DE.pdf).

#### fx-9860 GIII and fx-CG50
1. Connect Casio fx-9860 GIII of fx-CG50 to your Computer with the help of the USB cable.

**On the Calculator:** <br>

2. Press [F1]. (USB-Massensp)

**On your machine:** <br>

3. Open the file manager of your operating system and copy all [.g1m](#program_files) (for fx-9860 GIII) files or all [.g3m]() (fx-CG50) files into the shown device (usually D:) under D:/@MainMem/PROGRAM.

4. Eject device (usually D:). More info on calculator display.

**On the Calculator:** <br>

5. Press [EXE] as shown on the screen. <br>
6. Press [EXIT] as shown on the screen. <br>
7. Press [MENU] as shown on the screen. <br>

**Note**
Installation is also possible via the 3-Pin cable betweeen calculators.

| transmiting calculator | reciving calculator |
| ----------------- | ----------------- |
|fx-9860 GIII | fx-9860 GIII | 
| fx-9860 GII | fx-9860 GII |
| fx-9860 GII | fx-9860 GIII |
| fx-9860 GIII | fx-9860 GII |
| fx-9860 GIII | fx-CG50 |
| fx-CG50 | fx-CG50 |

### via 3-Pin
1. go into the LINK menu on both calculators [ALPHA] [E]
2. make sure that "Kabeltyp" is **3pin**
   
   If not [F4] (CABL) + [F2] (3PIN)
   
| transmiting calculator | reciving calculator |
| ----------------- | ----------------- |
| [F1] (TRAN)| |
|| [F2] (RECV) |
| [F1] (MAIN)| |
| [F1] (SEL)| |
| Go down to "< PROGRAM >" and press [EXE]. | |
| Select all files you want to transmit with arrows and [F1] (SEL) or press [F2] (ALL) to select all. | |
| If you finished press [F6] (TRAN) to transmit the selected files. | |
| If you get asked for confirmation press [F1] (Ja) | |
| Press [EXIT] as shown on the screen.| |
| | Press [EXE] as shown on the screen.|
| | Press [EXIT] as shown on the screen.|
| | [MENU] |

## How to use
To use the Progam you have to execute the ABI 2025.g1m file by:

**On the Calculator:** <br>
1. go into the Program menu [B]
2. execute the ABI 2025 file [EXE]

All the other files are used by the program automaticaly and you are getting redirected during execution. So don't rename them!

For a detailed List/Map of the included functionality see [menu_structure](/menu_structure.txt)

<div id=program_files> 
  
## Progam Files

| Filename   | Filesize on Calculator | Lines of code |
| ---------- | ---------------------- | ------------- |
| ABI 2025   | 2056 Bytes             | 58  Lines     |
| ABIA1 25   | 3024 bytes             | 212 Lines     |
| ABIA2 25   | 128  Bytes             | 7   Lines     |
| ABIG1 25   | 4248 Bytes             | 335 Lines     |
| ABIG2 25   | 3344 Bytes             | 381 Lines     |
| ABIG3 25   | 3232 Bytes             | 113 Lines     |
| ABIG4 25   | 1012 Bytes             | 51  Lines     |
| ABIG5 25   | 1716 Bytes             | 121 Lines     |
| ABIS1 25   | 5740 Bytes             | 371 Lines     |
| **Total**  | **24.500 Bytes**       | **1649 Lines**|

</div>

## Diclaimer
The links contained in this file allow you to leave this file and jump to other websites. I, Felix Wittwer, am not responsible for the content, links, changes or updates of these external websites. Use at your own risk!
