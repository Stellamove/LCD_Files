# LCD_Files

There are reports that some customers who have purchased the Ender-3 V2 from around February 2022 have started receiving the Ender-3 V2 with the new LCD model.

- Original DWIN company LCD (DMT48270C043_04WN)

   ![Original](https://user-images.githubusercontent.com/96027590/160739673-da6cefa5-aecd-47f4-b4ac-e7bdbee6d9c3.jpg)

- New DACAI company LCD

   ![DACAI](https://user-images.githubusercontent.com/96027590/160739604-999c6b64-5a9f-4268-8170-a53d8b7b100c.jpg)

# LCD Firmware Upgrade

1. Prepare SD card of 8GB or less (formatted as FAT32, 4096 allocation unit size)
2. Download DWIN_SET.zip for old stock LCD or private.zip for DACAI new LCD
3. Unzip DWIN_SET.zip or private.zip
4. Copy **"DWIN_SET"** or **"private"** folder to SD card
5. Turn off the Ender-3 V2 and remove the LCD unit
6. After disassembling the LCD case, insert SD card into SD slot of LCD PCB
7. Connect the LCD unit to Ender-3 V2 and turn on the Ender-3 V2
8. Wait for the upgrade to complete
   - When DWIN LCD upgrade is completed, the blue screen changes to orange screen (15 ~ 20 seconds)

      ![upload_orange](https://user-images.githubusercontent.com/96027590/160743404-54f73bff-4f23-4674-b9e9-6c69251ac3e2.jpg)

   - DACAI LCD upgrade progress is indicated by %

      ![upload_process](https://user-images.githubusercontent.com/96027590/160743433-dc306dad-0d01-4379-8a2e-1d86016cf970.jpg)

9. Turn off the Ender-3 V2 and remove the SD card from the LCD PCB's SD slot
10. After assembling the LCD unit, connect to Ender-3 V2
