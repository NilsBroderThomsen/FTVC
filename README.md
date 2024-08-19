# Fast Taskbar Volume Control (FTVC)

## Overview
**Fast Taskbar Volume Control (FTVC)** is a Windows utility designed to enhance user productivity by providing a quick and intuitive way to adjust the volume of individual applications directly from the taskbar. By holding the Shift key and scrolling the mouse wheel over a taskbar item, you can easily control the volume of the corresponding program. The application also includes a small overlay that displays the current volume level next to the taskbar preview window.

## Features
- **Taskbar Volume Control**: Adjust the volume of specific applications by hovering over their taskbar icons and scrolling the mouse wheel.
- **Shift Key Activation**: The volume control is activated only when the Shift key is held down, preventing accidental changes.
- **Visual Volume Indicator**: A discreet overlay shows the current volume level of the hovered application, displayed near the taskbar preview.
- **Designed for Windows 11**: Optimized for use with Windows 11, but should work on other recent versions of Windows.

## Installation
1. Download the latest release from the [Releases](https://github.com/NilsBroderThomsen/FastTaskbarVolumeControl/releases) page.
2. Extract the contents of the zip file to a directory of your choice.
3. Run `FTVC.exe` to start the application.

## Usage
1. **Launch FTVC**: Double-click `FTVC.exe` to start the program. The application will run in the background.
2. **Adjust Volume**:
    - Hold the Shift key.
    - Hover your mouse over the application icon in the taskbar.
    - Scroll the mouse wheel up to increase the volume or down to decrease the volume.
3. **View Volume Level**: A small overlay will appear next to the taskbar preview window, showing the current volume level of the application.

## Development
### Prerequisites
- **Visual Studio 2022 or later** with the **.NET Desktop Development** workload installed.
- **.NET 6.0 SDK** or later.

### Contributing
Contributions are welcome! If you have any ideas for new features or improvements, please open an issue or submit a pull request.

### License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Roadmap
- [ ] Implement volume control for individual audio channels (e.g., left and right).
- [ ] Add support for custom key combinations for activation.
- [ ] Create an options menu to configure settings such as sensitivity of volume changes.
- [ ] Enhance compatibility with older versions of Windows.
