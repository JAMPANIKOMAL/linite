# LINITE

A fast, minimalist web app for generating batch-install commands for your favorite Linux software.

**Live Website:** [Linite](https://jampanikomal.github.io/linite/)

Linite streamlines the process of setting up a new Linux machine. Instead of installing applications one by one, you can select everything you need from a curated list, and Linite will generate a single, ready-to-paste command for your specific distribution.

## Features

- **Smart Selection:** Choose your system by its base (Debian, Fedora, Arch) or by its specific name (Ubuntu, Kali, Manjaro, etc.).
- **Installation Presets:** Use one-click presets for common roles like "Web Developer" or "Graphic Design" to get started even faster.
- **Dynamic Command Generation:** The install command is built in real-time as you select software and configure options.
- **Modern & Lightweight:** Built with vanilla JavaScript and no dependencies for maximum speed.
- **Client-Side Privacy:** The entire application runs in your browser. No data is ever sent to a server.

## How to Use

1. Go to the [Linite website](https://jampanikomal.github.io/linite/).
2. Select your Linux distribution from one of the two menus.
3. Choose a preset or manually select your desired software.
4. Configure the command options (e.g., add `sudo`).
5. Copy the generated command and run it in your terminal.

## Contributing

This project is open to contributions! The easiest way to help is by expanding the software and distribution lists. All application data is stored in simple `.json` files in the `/data/` directory.

1. Fork the repository.
2. Add a new application:
    - Add the app's metadata to `data/global.json`.
    - Add the package name to `data/debian.json`, `data/fedora.json`, and `data/arch.json`. If a package doesn't exist for a distro, use `null`.
3. Submit a pull request with a clear description of your changes.

## Acknowledgements

This project was developed by Jampani Komal with the collaborative assistance of Google's Gemini.

## License

This project is open source and available under the [MIT License](./LICENSE).