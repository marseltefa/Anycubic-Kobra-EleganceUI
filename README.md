# Anycubic Kobra EleganceUI
An improved beautiful UI for the Anycubic Kobra 3d printer

## Disclaimer
I am not responsible for any damage or malfunction caused to your printer because of those files. Any modding made to your printer is made at your own risk, this includes any damage that could happen in real life.

## Description
For my Anycubic Kobra I'm using the custom firmware form **jcst40** [Kobra-Kai-with-Thumbnail-preview](https://github.com/jcst40/Kobra-Kai-with-Thumbnail-preview) but I didn't like the UI so I made a new one which is based on **malebuffy's** [Kobra-Max-Cobra-Kai-UI-and-Firmware](https://github.com/malebuffy/Kobra-Max-Cobra-Kai-UI-and-Firmware). This is for the standard Kobra but in theory it should work for Max too I have no way to test it. You can try it for yourself.

![screenshot](/img/elegance_ui.png)

# How to install
### Updating your printer screen to the latest version
1. Go to your printer -> Settings -> About -> UI Version -> If you're on Anycubic_20211220 you can skip to installing the modded firmware
2. Head on to the official page of the Anycubic Kobra (https://www.anycubic.com/products/kobra)
3. Scroll down and download the Firmware V2.7.9 OR you can build your own firmware from the Anycubic Github repository (V2.8.2).
4. Follow the instructions in the Read Me.txt of their file.
5. If the installation succeed you should see ` SD card Process... END ` ! at the top, you can then turn off the printer and remove the SD card

### Install Custom Firmware
Install the custom firmware form **jcst40** [Kobra-Kai-with-Thumbnail-preview](https://github.com/jcst40/Kobra-Kai-with-Thumbnail-preview)

### Installing the modded UI firmware
1. Download the latest release in the release tab (https://github.com/marseltefa/Anycubic-Kobra-EleganceUI/releases/)
2. Unzip the DWIN_SET folder at the root of your SD card (make sure to use a reliable SD card), do not put anything else but this folder, if you had the old folder from the official firmware, remove it before
3. Turn off your printer put the SD card under the screen, not in the printer the body. Make sure to leave it unplugged for 10 - 20 seconds to make sure the caps can discharge
4. Turn on your printer and wait until you see ` SD card Process... END ! ` on the second line, do NOT turn off the printer before this line appears. The process shoudn't take more than 5 minutes unless your SD card is broken or very slow
5. Make sure the number next to .BIN Files shows ` 003 ` and the number next to .ICL Files ` 001 `
6. Turn off your printer, remove the SD card
7. Done, you can turn it on

![flash screen](/img/flash_screen.jpg)

# FAQ
### Can I revert to the old version if I don't like it?
Yes you can, just follow the steps to update the screen firmware to the latest version above
### Does this work with unmoded Kobra firmware?
I don't know maybe I haven't tried it since I'm using the custom firmware which is way better. I don't recommend you to use it with the standard firmware since the custom firmware has some extra graphics.
### Are there any risk in doing that?
I have no idea if updating the screen firmware by itself is risky or not, I have done it many times and it's working fine but I don't know. So to be safe follow good practice like don't turn off the printer while it's updating. The potential risks of using the custom UI itself could be that I did something wrong causing the printer to not behave as expected. You should always keep that in mind when installing this UI and read the disclaimer at the beginning.
