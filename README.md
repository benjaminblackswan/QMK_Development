# QMK Development


## How to update QMK Keymaps and flash the keyboard
1. go to `C:\Users\benja\qmk_firmware\keyboards\keychron\q1v1\ansi\keymaps\Ben_Keychron_Q1V1_QMK_Development`
2. Update the keymap
3. Open **QMK MSYS** program from Start menu
4. run the `qmk compile command`
  <img width="864" height="362" alt="image" src="https://github.com/user-attachments/assets/fa5d6bbf-9dfa-4e1c-9d00-de2582137467" />
  you should see five [OK]
  This will update the .hex file needed to flash your keyboard.
6. Run QMK Toolbox, this is not an installed software, so it is likely to be in the downloads folder.
7. Check Auto-Flash box
8. Click Open and select to the .hex file updated in step 4, it is located in `C:\Users\benja\qmk_firmware\.build`. Check the date and time of the .hex, it should be current.
   <img width="937" height="204" alt="image" src="https://github.com/user-attachments/assets/c592b795-9105-4499-ad0c-f7b40d2d398e" />
10. Put your keyboard into flash mode, this is the QK_BOOT macro in your keymap.
    <img width="950" height="650" alt="image" src="https://github.com/user-attachments/assets/75afdcbd-c5ed-48a6-be7b-0767d800903f" />
11. Create a copy of the keymap into `C:\Users\benja\OneDrive\Onedrive\Human Input Devices\Keyboard\QMK Development\Keychron Q1V1 Keymap Archive`
