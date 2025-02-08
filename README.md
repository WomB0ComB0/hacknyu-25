# Spend Wisely Extension

## Overview
The Spend Wisely Extension is a Chrome extension designed to provide users with insights and tools related to their spending habits. The extension features a user-friendly interface with components built using React, styled with Tailwind CSS, and incorporates the Poppins font for a modern look.

## Major Parts of the Code

1. **IndexPopup Component**: 
   - This is the main component that renders the popup when the extension is clicked. It retrieves the current active tab's URL using the Chrome API and displays it in the popup.
   - It also includes links to the Plasmo website and documentation, as well as a button that can be customized for future functionality.

2. **Button Component**: 
   - A reusable button component that utilizes the `class-variance-authority` library to manage variants (like size and style) and states (like disabled).
   - It supports different button styles such as default, destructive, outline, secondary, ghost, and link.

3. **Styles**: 
   - The extension uses global CSS styles and Tailwind CSS for layout and responsiveness.
   - Custom CSS variables for theming are defined, allowing for adjustments between light and dark modes.

4. **Font Integration**: 
   - The extension uses the Poppins font, with various weights and styles defined for use throughout the application.

5. **HTML Pages**: 
   - Several HTML files serve different parts of the extension, including the options page, side panel, new tab, dev tools, and the popup. Each of these pages loads a corresponding TypeScript file.

## Installation

To install and run the Spend Wisely Extension locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/spend-wisely-extension.git
   cd spend-wisely-extension
   ```

2. **Install dependencies**:
   Make sure you have Node.js and npm installed. Then run:
   ```bash
   npm install
   ```

3. **Build the project**:
   ```bash
   npm run build
   ```

4. **Load the extension in Chrome**:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" (toggle switch in the top right corner)
   - Click on "Load unpacked" and select the `build` directory of your cloned repository.

## Usage

1. **Using the Extension**: 
   - After loading the extension, an icon will appear in the Chrome toolbar.
   - Click the icon to open the popup, where you can see the current tab's URL and access links to the documentation.

2. **Interacting with the Button**: 
   - The button in the popup can be customized to perform actions in the future. Currently, it serves as a placeholder for future functionality.

3. **Documentation**: 
   - For more detailed information about the extension and its components, visit the [Plasmo documentation](https://docs.plasmo.com).

## License
This project is licensed under the SIL Open Font License, Version 1.1. See the LICENSE file for details.

## Contributing
Feel free to open issues or submit pull requests for improvements or features. Your contributions are welcome!

## Acknowledgements
- Thanks to the contributors and the community for their support and contributions to this project.