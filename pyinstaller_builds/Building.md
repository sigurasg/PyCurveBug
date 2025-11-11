## Building Native OS releases with PyInstaller
By building native OS releases we can allow others to use a native application without needing python or any other of PyCurveBug requirements.

#### Building Usage:
Copy `PyCurveBug.py` and `curvebug_config.json` files in the same directory as `build.py` (pyinstaller_build)

#### Run Build Script:
* Windows: `python build.py` or double-click `build_windows.bat`
* Linux: `python3 build.py` or `./build_linux.sh`
* Linux/Mac: `python3 build.py` or `./build_macos.sh`

The script should create a `dist` folder with your compiled executable and distribution packages.

Get in touch with me, so I can upload your Linux/MacOS build in the releases section as I'm only able to build for Windows.