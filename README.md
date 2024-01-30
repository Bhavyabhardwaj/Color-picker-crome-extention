# Chrome Extension Color Picker

## Description

This Chrome extension provides a simple color picker tool allowing users to pick and store colors from their web browsing experience. The picked colors are displayed in a list with their hex values.

## Features

- **Color Picking:** Click the color picker button in the extension popup to activate the eye dropper tool. Select a color on any web page.

- **Clipboard Copy:** The selected color's hex code is copied to the clipboard automatically.

- **Color History:** View a list of picked colors along with their hex codes. The history is saved locally using browser storage.

- **Clear All:** Clear all picked colors and hide the color history.

## Usage

1. Click the extension icon in the toolbar.
2. Click the color picker button to activate the eye dropper tool.
3. Select a color on any web page.
4. The picked color is copied to the clipboard and added to the color history.

## Local Development

Clone the repository:

```bash
git clone https://github.com/Bhavyabhardwaj/Color-picker-crome-extention.git
```

Load the extension in Chrome:

1. Open Chrome and go to `chrome://extensions/`.
2. Enable "Developer mode" at the top right.
3. Click "Load unpacked" and select the cloned repository folder.

## Dependencies

This Chrome extension relies on the browser's EyeDropper API for color picking.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
