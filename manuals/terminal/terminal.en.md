# User Manual: Settings for Web-Based Terminal App

## Introduction
Welcome to the settings manual for your web-based terminal application. This document will guide you through the various customizable options available in the settings menu, allowing you to personalize your terminal experience according to your preferences.

## Settings Menu Overview
The settings menu provides several options for adjusting the appearance and functionality of your terminal. Below, you'll find detailed descriptions and instructions for each setting.

### 1. Choose a Theme
The "Choose a Theme" dropdown allows users to select different visual themes for their terminal interface. These themes are sourced from [Gogh](https://gogh-co.github.io/Gogh/), providing a variety of color schemes to enhance the look and feel of your terminal.

- **How to Use**: Click the dropdown to select a theme from the available options. Initially, no themes are available until you click "Add More Themes".
- **Note**: Themes are pre-defined, and users cannot import custom themes directly. For more options, visit the Gogh website linked above.

### 2. Add More Themes
The "Add More Themes" button allows users to extend the available theme options by fetching them from an external source.

- **How to Use**: Click this button to send an HTTP request that pulls themes from a remote `themes.json` file. Once fetched, the new themes will appear in the "Choose a Theme" dropdown.
- **Note**: Without clicking this button, only the default theme will be available.

### 3. Font Size (px)
The "Font Size" input box lets users adjust the font size across all elements of the terminal.

- **How to Use**: Enter a value (in pixels) to change the font size for command inputs, outputs, and prompts. The default value is set to **14px**.
- **Tip**: Larger font sizes may enhance readability, while smaller sizes allow more information to fit on the screen.

### 4. Proxy
The "Proxy" field is used to specify a CORS proxy URL for handling HTTP/HTTPS requests targeting API endpoints.

- **How to Use**: Enter the desired proxy URL to route network requests through it. This can help with privacy or bypassing CORS restrictions.
- **Note**: You can optionally provide an API key if needed, but most pre-configured APIs do not require authentication.

### 5. Prompt
The "Prompt" input box allows users to set a static prompt string that appears in the terminal.

- **How to Use**: Enter any static text to customize the prompt for the terminal. This text will appear before each command you type.
- **Note**: Since this is a browser-based terminal, the prompt cannot include dynamic variables like the current directory or username.

### 6. Color
The "Color" dropdown allows users to change the color of output messages in the terminal.

- **How to Use**: Select one of the **8 available colors** from the dropdown to customize the appearance of command output text.
- **Note**: This setting changes the color of output messages only, using special character sequences to achieve the effect.

### 7. Open Editor
The "Open Editor" button opens a web-based editor for modifying the current terminal configuration.

- **How to Use**: Click this button to access an integrated editor where you can adjust terminal settings or write custom JavaScript functions.
- **Tip**: You can find common functions and examples at [GitHub - yuxiaoli/scripts](https://github.com/yuxiaoli/scripts/tree/main/src/js/terminal).

### 8. Copy URL
The "Copy URL" button generates a snapshot of the current terminal configuration and converts it into a shareable URL.

- **How to Use**: Click the button to copy the URL to your clipboard. You can share this URL with others, allowing them to replicate your current setup.
- **Note**: No special permissions are required to share the URL, as it does not involve session authentication.

### 9. Back
The "Back" button is used to close the settings menu and return to the main terminal screen.

- **How to Use**: Click "Back" to exit the settings menu. Any changes made are saved dynamically, so there's no need to restart the terminal.
- **Note**: Changes take effect immediately, without requiring a reload of the application.

## Tips for Optimal Use
- **Font Size**: The default value of 14px is recommended for most users, but feel free to adjust it for comfort.
- **Themes**: Click "Add More Themes" to explore and apply different color schemes to improve the terminal's aesthetic.
- **Proxy**: Using a proxy can help bypass restrictions, but be cautious when entering URLs to ensure data safety.

## Troubleshooting
- **Themes Not Showing**: Make sure to click "Add More Themes" to populate the theme dropdown.
- **Font Size Not Changing**: Verify that the entered value is a positive integer.
- **Settings Not Saving**: Changes are saved dynamically. If settings don't seem to update, try refreshing the browser.

## Conclusion
The settings menu of your web-based terminal app offers a range of customization options to improve your experience. Experiment with different settings to find what works best for you. If you need further assistance, consult the tips or troubleshooting section above.

Happy terminaling!