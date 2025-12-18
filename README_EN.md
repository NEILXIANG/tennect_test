# Hello World macOS Executable

## Description

A simple macOS executable that prints "iloveyou" to the console and waits for user input before closing.

## Files

- `main.py` - Python source code
- `hello_world` - macOS executable file (after building)

## Usage

### Run from source
```bash
python3 main.py
```

### Run executable (after building)
```bash
chmod +x hello_world
./hello_world
```

## Features

- ✅ No Python environment required
- ✅ Single file distribution
- ✅ Works on Intel and Apple Silicon Mac
- ✅ Waits for user input before closing
- ✅ Cross-platform compatibility

## System Requirements

- macOS 10.13 or later
- Intel or Apple Silicon Mac

## Output

When running the program, you will see:
```
iloveyou

Press Enter to exit...
```

The program will wait for you to press Enter before closing.

## Building

To build the executable:

```bash
# Install PyInstaller
pip install pyinstaller

# Build the executable
pyinstaller --onefile --name hello_world main.py
```

The executable will be created in the `dist/` directory.

## Distribution

Copy the `hello_world` executable file to any macOS machine and run it directly - no additional dependencies required.

## Version History

- v1.0: Initial release with basic functionality
- v1.1: Added user input wait before closing