# FileOper
Open Your File Manager from Terminal

# Directory Opener Script

This Bash script prompts the user to enter a directory path and opens it using the system's default file manager. If the provided directory exists, it utilizes the `xdg-open` command to open the directory. If the directory does not exist, it displays an error message.

## Usage
1. Run the script.
2. Enter the path of the directory you want to open when prompted.

## Requirements
- Bash shell
- xdg-utils for opening the file manager

## Usage Example
./fileoper

