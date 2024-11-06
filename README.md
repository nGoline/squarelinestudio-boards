Here’s an expanded README file with the required information:

# SquareLine Studio Boards for CYD

This repository provides configurations for several ESP32 display boards that can be integrated with SquareLine Studio to simplify development.

## Installation

1. **Locate the SquareLine Studio installation path** on your operating system:
   - **Windows**: `C:\Program Files\SquareLine Studio\boards\`
   - **macOS**: `/Users/[your-user-name]/SquareLine/boards/`
   - **Linux**: `/opt/squareline-studio/boards/`

2. **Copy the `CYD` folder** into the `boards` directory within the SquareLine Studio installation path. This should result in the following structure:

```
/boards/CYD/esp32_3248s035C/v1_0_0/
/boards/CYD/esp32_4827s043C/v1_0_0/
/boards/CYD/esp32_8048s043C/v1_0_0/
```

3. **Restart SquareLine Studio** if it was open during the file copy.

## Demo

A demo project is included with each board configuration. To use the demo:
1. Create a new project in SquareLine Studio.
2. Select the desired board model from the list of available boards.
3. Export the project to explore how to work with these boards in SquareLine Studio.

## Requesting Additional Boards

If you'd like support for additional boards, I’d be happy to add them as long as you can assist with testing on the actual hardware. Simply open an issue in this repository and include the board model, relevant links, and any other helpful information.

Enjoy easier development with SquareLine Studio and your CYD-compatible ESP32 boards!