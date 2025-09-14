# hidescreenAHK-windows

A tiny [AutoHotkey](https://www.autohotkey.com/) script that adds a **macOS-like "hide window" shortcut** to [Windows](https://www.microsoft.com/windows).

## Features
- Press **Win + H** to hide the current active window from view
- The window is only **minimized**, not closed
- It stays visible in **Alt+Tab** and **Win+Tab** so you can bring it back easily

## Run on Startup
To make the script run automatically every time you log in:

1. Press `Win + R`
2. Type `shell:startup` and press Enter  
   *(This opens your Startup folder)*
3. Go to the folder where your `.ahk` script is saved
4. Right-click your `.ahk` file → **Copy**
5. Go back to the Startup folder → Right-click → **Paste shortcut**

## Notes
- This script uses `WinMinimize` instead of `WinHide` so windows remain visible in task switchers

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, reach out via email:
- **Email**: jred8069@gmail.com

