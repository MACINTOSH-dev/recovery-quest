# Firmware recovery Meta/Oculus Quest 2/3s/3/Pro

## Choose your language
**English** | [`Pусский`](/README.md)

>[!NOTE]
> If for some reason your headset, for example after a firmware update in Russia (relevant for Quest 2), does not load into the OS, or there is a gray screen after the Meta logo, **maybe** this guide will help you solve this problem

If you have any problems, you can write to me (https://t.me/neonris)

## Preparation
> Download the archive [adb](https://github.com/MACINTOSH-dev/recovery-quest/releases/download/adb/adb.zip), and then download the **latest firmware** for your model (it must be the latest, this is important!)

#### Downloading firmware for your helmet
> On [this site](https://cocaine.trade/) select your helmet model, then a page with firmware should open, **click on the very top** in the ***Incremental*** column, after that, the download will begin.
 
#### Archive preparation
> You should have downloaded a .zip file (for example q3_51312300200800520), **you don't need to unzip it**, rename it to *Update* (it should look like this: Update.zip)

## Start
> Unzip the adb archive somewhere, for example **C:\adb**, and then place the newly renamed file into the unzipped folder: Update.zip
Then open CMD as administrator and run the command. Replace `path\to\` with the actual path to the adb folder you just unzipped. For example: *C:\adb*
```cmd
cd path\to\adb
```
#### Putting the helmet into download mode

> Turn off the headset completely, making sure it is charged to at least 30%, then simultaneously press and hold the power and volume down buttons until the loading screen appears.

<img align="center" src="https://github.com/MACINTOSH-dev/recovery-quest/blob/main/photo.png" width="350" alt="USB Update Mode">


Next, select "Sideload update" using the volume buttons, then press the power button to confirm. The headset's indicator should turn purple. Now, connect it to your PC using a cable. (Use a data cable, such as the Link cable or the charging cable that came with your headset.)

### Firmware
>[!Warning]
> **All data on the headset will be erased, including games, account data, and general settings. You've been warned.**

> In the cmd window, run the following command
```cmd
adb.exe sideload ./Update.zip
```
The firmware process will begin, and upon completion, the helmet will reboot itself and should boot into the OS.

# Finish!



## Troubleshooting

If your headset does not enter Sideload mode, after pressing it reboots again into USB Update Mode, **at the moment you will not be able to restore the headset using the available methods.** The only working option is to replace the motherboard with a working one.



