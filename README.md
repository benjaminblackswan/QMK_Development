# QMK Development


## How to update QMK Keymaps and flash the keyboard
1. go to `C:\Users\benja\qmk_firmware\keyboards\keychron\q1v1\ansi\keymaps\Ben_Keychron_Q1V1_QMK_Development`
2. Update your keymap
3. Open **QMK MSYS** program from Start menu
4. run the `qmk compile command`
  <img width="864" height="362" alt="image" src="https://github.com/user-attachments/assets/fa5d6bbf-9dfa-4e1c-9d00-de2582137467" />

  You should see five [OK]s. This will update the .hex file needed to flash your keyboard.
  
6. Run **QMK Toolbox**, this is not an installed software, so it is likely to be in the downloads folder.
7. Check Auto-Flash box tick box.
8. Select `ATmega34U4`.
9. Click Open and select to the .hex file updated in step 4, it is located in `C:\Users\benja\qmk_firmware\.build`. Check the date and time of the .hex, it should be recently built.
   <img width="945" height="215" alt="image" src="https://github.com/user-attachments/assets/9eb13e03-53b6-42bc-b6ff-99cc27aecf1a" />

10. Put your keyboard into flash mode, this is the `QK_BOOT` macro in your keymap that you flashed previously.
    <img width="950" height="650" alt="image" src="https://github.com/user-attachments/assets/75afdcbd-c5ed-48a6-be7b-0767d800903f" />
11. Create a copy of the keymap into `C:\Users\benja\OneDrive\Onedrive\Human Input Devices\Keyboard\QMK Development\Keychron Q1V1 Keymap Archive`
