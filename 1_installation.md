# Installation

## Windows

1. **Download**: Go to the Zig official download page (<https://ziglang.org/download/>) and download the appropriate `.zip` file for Windows.
2. **Extract**: Extract the `.zip` file to a location of your choice.
3. **Add to Path**: Add the extracted folder to your system's PATH environment variable to make the `zig` command available from anywhere in the command prompt.

## macOS

1. **Homebrew**: If you have Homebrew installed, you can simply run `brew install zig`.
2. **Manual Installation**: Alternatively, download the `.tar.xz` file from the Zig download page, extract it, and add the bin folder to your PATH.

## Linux

1. **Package Manager**: Many Linux distributions include Zig in their package managers. For example, on Ubuntu, you can use `sudo apt-get install zig`.
2. **Snap**: Zig can also be installed via Snap with `sudo snap install zig --classic`.
3. **Manual Installation**: Like with macOS, you can download the `.tar.xz` file, extract it, and add the bin directory to your PATH.

### General Steps for Manual Installation

For manual installations, after downloading and extracting Zig, you generally need to:

- **Extract the Archive**: Use appropriate tools like `tar` for Linux/macOS or an archive manager on Windows.
- **Add Zig to PATH**: Modify your shell's profile script (e.g., `.bashrc`, `.zshrc`, or the Windows environment variables) to include the path to the Zig binary.

### Verify Installation

After installation, you can verify it by opening a terminal or command prompt and running:
