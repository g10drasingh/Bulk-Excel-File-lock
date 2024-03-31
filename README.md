# Bulk Excel File Lock/Unlock Utility

This repository contains VBA macros to bulk protect or remove passwords from Excel files within a specified folder. These macros are designed to streamline the process of securing or unlocking multiple Excel files in a folder with a common password at once.

## Lock_Files_VBA
This VBA macro protects multiple Excel files within a chosen folder by setting a password.

### Usage
1. Open the Excel file where you want to apply the macro.
2. Press `ALT + F11` to open the VBA editor.
3. Insert a new module by going to `Insert` > `Module`.
4. Copy and paste the code from [`Lock_Files_VBA`](https://github.com/g10drasingh/Bulk-Excel-File-lock/blob/main/Lock_Files_VBA) into the module.
5. Close the VBA editor.
6. Run the `ProtectAll` macro from the Excel file. Follow the prompts to select the folder containing the Excel files and specify the password.

## Unlock_Files_VBA
This VBA macro removes password protection from multiple Excel files within a chosen folder.

### Usage
1. Open the Excel file where you want to apply the macro.
2. Press `ALT + F11` to open the VBA editor.
3. Insert a new module by going to `Insert` > `Module`.
4. Copy and paste the code from [`Unlock_Files_VBA`](https://github.com/g10drasingh/Bulk-Excel-File-lock/blob/main/Unlock_Files_VBA) into the module.
5. Close the VBA editor.
6. Run the `RemovePassword` macro from the Excel file. Follow the prompts to select the folder containing the Excel files and specify the password.

## How to Use the Macros
- Both macros prompt the user to select a folder containing the Excel files to process.
- Users must provide a password to either protect or unlock the Excel files.
- Ensure macros are enabled in Excel settings before running.

## License
This project is licensed under the [MIT License](LICENSE).
