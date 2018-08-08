# TI-89

I've been writing programs in TI Basic since ~1998. For my Mechanical Engineering coursework I would study by writing programs. I found that by breaking down the problems by programming them I tricked myself into actually learning the material.

I recently found my TI-89s and pulled all of the files using tilp2.

Tested and written on TI-89 and TI-89 Titanium. Should work with TI-92 as well.

## Courses

- [ME 365: Systems and Measurements](pdfs/me365.pdf)
- [ME 572:  Design and Analysis of Robotic Manipulators](pdfs/me572.pdf)
- [ME 575: Theory and Design of Control Systems](pdfs/me575.pdf)
- [STAT 514: Design of Experiments](http://www.stat.purdue.edu/~kuczek/stat514/)

## Usage on Android

- [Graph 89](https://f-droid.org/en/packages/com.Bisha.TI89EmuDonation/) TI-89 Emulator Software.
- [TI-89 Titanium Operating System](https://education.ti.com/en/software/details/en/6633925F6176419197BF6CA051F5F7B4/89ti89tioperatingsystem) [[TI89Titanium_OS.89u](https://education.ti.com/download/en/ed-tech/6633925F6176419197BF6CA051F5F7B4/1220AE887C2944FB824D351577A13021/TI89Titanium_OS.89u)]
- Zip of this repository: https://github.com/jed-frey/TI-89/archive/master.zip;


1. Unzip the folder somewhere on your Android device.
2. Run Graph 89 and select your ROM.
3. Open the menu and add the files.
4. Run them as they were on the TI-89.

## Usage on Linux.

Tested on Ubuntu 18.04.

Setup:

1. tiemu: ```sudo apt-get install tiemu```
2. Download ```TI89Titanium_OS.89u``` to the current directory.
3. Run ```tiemu TI89Titanium_OS.89u```.

Or run ```ubuntu1804.sh```

1. Press F10 or right click and "Send File To TIemu...".
2. Load all of the files.
3. Right Click: Calculator state > Save state image...
4. Save the ROM & Memory.

In the future you just need to run ```tiemu TI89Titanium_OS.sav```.

## Usage on TI-89.


1. Figure out how to connect to a TI-89 in 2018.
  - [TI-GraphLink](https://education.ti.com/en/software/details/en/A2E9B3DFCB44490DBD5449E05721767D/ti-graph-link-for-windows)
  - [TI-Connect](https://education.ti.com/en/products/computer-software/ti-connect-sw)
2. Send them to the TI-89.