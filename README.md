# LINITE - Brutalist Batch Installer for Linux

Linite is a fast, minimalist web interface for generating a single installation command for multiple Linux applications, tailored to your distribution. Inspired by Ninite for Windows, Linite features a stark, brutalist design for clarity and efficiency.

## Features

- **Distribution Selection:** Choose from Debian/Ubuntu, Fedora/CentOS, or Arch/Manjaro families.
- **Categorized Software:** Browse popular apps organized into categories like Browsers, Development, and Utilities.
- **Dynamic Command Generation:** Instantly build a ready-to-paste shell command as you select software.
- **Availability Check:** Apps not available in your chosen distribution's repositories are automatically disabled.
- **Client-Side Only:** Runs entirely in your browser—no data sent to servers.

## How to Use

1. Open `index.html` in your web browser.
2. Select your Linux distribution family.
3. Check the boxes for the software you want to install.
4. Copy the generated command from the output box.
5. Paste and run the command in your terminal.

## Design Philosophy

Linite follows the [SYSTEM ZWEI] brutalist design system:

- **Monochrome Palette:** Pure black and white for maximum contrast.
- **Monospace Typography:** Uses Space Mono for a technical, uniform look.
- **Hard Borders & Sharp Corners:** No rounded corners or shadows—structure is celebrated.
- **Function Over Form:** Every element is direct and purposeful.

See the Brutalist Design System Documentation for more details.

## Contributing

Linite is a single-file vanilla HTML/JS/CSS project. Contributions are welcome:

1. Fork the repository.
2. Make your changes (e.g., add new software to `softwareData` in `index.html`).
3. Document your changes clearly.
4. Submit a pull request.
