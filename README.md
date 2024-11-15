# CloudHyper Custom

CloudHyper Custom is a dynamic web-based tool that allows users to create multiple files in various programming languages, write code for each file, and download them all in a single ZIP file. Built with JavaScript and leveraging the JSZip library, CloudHyper Custom is designed to support coding in a highly customizable and user-friendly environment.

## Features

- **Create Multiple Files**: Easily create multiple files with custom file names and extensions.
- **Write Code**: Input code for each file in any programming language of choice.
- **Download as ZIP**: Download all created files as a single ZIP file.
- **Modern UI**: Enjoy a dark-themed, stylish interface with advanced styling for an improved user experience.

## Usage

To use CloudHyper Custom, visit the live version here:  
**[CloudHyper Custom](https://calestialashley35.github.io/CloudHyper-Custom/)**

### Steps

1. Click the **Create File** button.
2. Enter a **file name** (with extension, e.g., `script.js`, `style.css`, etc.).
3. Write the **code content** for the file.
4. Repeat steps 1-3 to create as many files as needed.
5. Click the **Download as ZIP** button to download all files in a ZIP archive.

## Getting Started Locally

If you prefer to run CloudHyper Custom locally, download the project files and open `index.html` in your browser.

### Prerequisites

This project requires no backend or external libraries beyond JSZip, which is included via a CDN.

## Code Overview

### HTML and JavaScript

The project includes a basic HTML structure with JavaScript functionality for creating and managing files:

- `createFile` button: Prompts for a file name and code content, then stores the file data.
- `downloadZip` button: Uses JSZip to compile all files into a ZIP file and triggers a download.
- **JSZip**: A library for creating ZIP files in JavaScript, included via a CDN.

### CSS Styling

The interface is designed with modern CSS styling:
- **Dark Theme**: Dark background and light text for a sleek look.
- **Animated Buttons**: Gradient buttons with hover effects for better user interaction.
- **File Cards**: Each file is displayed in a visually distinct "card" for easy identification.

## Technologies Used

- **HTML**: Provides the structure for the interface.
- **CSS**: Styles the interface with a modern, dark theme.
- **JavaScript**: Handles file creation, code entry, and ZIP file download functionality.
- **JSZip**: Allows for ZIP file creation and download in JavaScript.

## Future Enhancements

- **Syntax Highlighting**: Add syntax highlighting for better readability in the code preview.
- **Advanced File Management**: Include options to edit, rename, or delete files.
- **Multiple Language Support**: Add language-specific features or templates for common file types.

## License

This project is open-source and available under the MIT License.

---

Enjoy coding with **CloudHyper Custom**!
