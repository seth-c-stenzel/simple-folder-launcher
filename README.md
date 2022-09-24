# Simple Folder Launcher
## About
This is a simple utility that allows me to create a custom folder launcher with a folder icon with pyinstaller.
The end goal is to be able to pin the exe to the Windows taskbar, as Windows does not allow you to pin folders directly.

## Usage
Modify `simple_folder_launcher.py` modify the directory at the end of the file before the main() call.
Then build the app with pyinstaller using autopytoexe command in the terminal.

1. > autopytoexe
2. Select the `simple_folder_launcher.py` file.
3. Set as single file build.
4. Choose/set the icon file.
5. Set exe type to Window Based (not console based).
6. Build with `Convert .PY to .EXE`
7. Once build place the exe wherever you choose.
8. Right-click and choose pin to taskbar.