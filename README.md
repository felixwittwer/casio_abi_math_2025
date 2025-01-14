[![Generic badge](https://img.shields.io/badge/newest_version-2025.1.1-<COLOR>.svg)](https://github.com/felixwittwer/casio_abi_math_2025/releases)
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

In rare cases there are also Versions with year . main version. subversion DEV
These are temporary development versions that are not quite ready for release

### 2025.1.1
- add "Zurück" to Panic Button menu (fix issue #46)
- add Info zu PaB Menü menu to explain the Panic Button menu and it's functionality

### 2025.1.0
- allow area of triangle to be calculaed with two vectors (fix issue #45)
- Redundancy of point to point to line conversion (fix issue #44)
- Redundancy of triangle menu (fix issue #43)
- increase number of digits in point to point result (fix issue #42)
- add Panic Button (fix issue #41)
- Normalverteilungsmenu is missing cls commands (fix issue #40)

### 2024.1.5
- replace SolvN with Solve when possible (fix issue #39)
- binomial distribution calculation (fix issue #38)
- Add sigmarules (fix issue #37)
- normal distribution search for intervall (fix issue #36)
- Math Error in binomial distribution menu (fix issue #35)
- autoinsert of binomial and normal distributions into graphics menu (fix issue #34)

### 2024.1.4
- hide functions after use in program (fix issue #33)
- find unknown height within Rotationsvolumen (fix issue #32)
- Mathematial Error at sequence command (fix issue #31)
- Add Rotationsvolumen for Objects cosisting of two functions (fix issue #30)
- Add Rotationsvolumen calculation between two functions (fix issue #29)
- Ebenengleichungen asks for to many inputs (fix issue #28)
- Fix dimension error when there area intersection points (fix issue #27)
- Add settings menu (fix issue #26)
- find unknown parameters of function with integral menu (fix issue #25)
- adding multiple Standardabweichungen von Erwartungswert (fix issue #23)

### 2024.1.4DEV
- Fix dimension error when there area intersection points (fix issue #27)
- Add settings menu (fix issue #26)

### 2024.1.3
- add integral menu (fix issue #24) 

### 2024.1.2
- fix dimension errors in Analysis menu (fix issue #22)

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

When the program ist insalled go into the "Einstellungen" (Settings) menu and select "Zurücksetzen" (Reset) this initializes all settings so the program can use them. If you do not do this step some menus will not work!

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


When the program ist insalled go into the "Einstellungen" (Settings) menu and select "Zurücksetzen" (Reset) this initializes all settings so the program can use them. If you do not do this step some menus will not work!

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
| ABI 2025   | 3964 Bytes             | 102 Lines     |
| ABIA1 25   | 4044 bytes             | 278 Lines     |
| ABIA2 25   | 128  Bytes             | 7   Lines     |
| ABIA3 25   | 2152 Bytes             | 121 Lines     |
| ABIG1 25   | 4248 Bytes             | 335 Lines     |
| ABIG2 25   | 3352 Bytes             | 376 Lines     |
| ABIG3 25   | 3620 Bytes             | 124 Lines     |
| ABIG4 25   | 1084 Bytes             | 53  Lines     |
| ABIG5 25   | 1720 Bytes             | 122 Lines     |
| ABIS1 25   | 6580 Bytes             | 375 Lines     |
| ABIS2 25   | 1752 Bytes             | 80  Lines     |
| **Total**  | **32.644 Bytes**       | **1973 Lines**|

</div>

## Diclaimer
The links contained in this file allow you to leave this file and jump to other websites. I, Felix Wittwer, am not responsible for the content, links, changes or updates of these external websites. Use at your own risk!
