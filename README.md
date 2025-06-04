# tgpt Installer for Termux

## Installation

1. Ensure you have `curl` installed:
   ```
   pkg install curl
   ```
2. Run the installation script:
   ```
   bash <(curl -s https://raw.githubusercontent.com/aandrew-me/tgpt/main/termux-install.sh)
   ```
   This will download the appropriate binary for your system architecture and install it in the `$PREFIX/bin` directory.

## Usage

After installation, you can run the `tgpt` command to use the tool. For help, run:
```
tgpt -h
```

## API

The `tgpt` tool provides a command-line interface. Refer to the help output for the available options and usage.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/aandrew-me/tgpt).

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

The installation script includes basic error handling and validation. However, it is recommended to test the installation on your specific Termux environment to ensure it works as expected.
