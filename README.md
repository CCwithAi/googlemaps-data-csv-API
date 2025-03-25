# Google Maps to CSV

A Chrome extension that allows you to easily scrape Google Maps search results and download the data as CSV files.


## For Users

### Installation

#### Method 1: Install from Chrome Web Store (Recommended)(coming soon)
1. Navigate to the Chrome Web Store (coming soon)
2. Search for "Google Maps to CSV" or use the direct link
3. Click "Add to Chrome"
4. Confirm the installation when prompted

#### Method 2: Manual Installation
1. Download the latest release from the  page (or download this repository as a ZIP file)
2. Extract the ZIP file to a location on your computer
3. Open Chrome and navigate to `chrome://extensions/`
4. Enable "Developer mode" using the toggle in the top-right corner
5. Click "Load unpacked"
6. Browse to the folder where you extracted the extension and select it
7. The extension should now appear in your extensions list and be ready to use

### Usage

1. Navigate to Google Maps in Chrome (https://www.google.com/maps)
2. Search for businesses, places, or services you want to scrape (e.g., "coffee shops in New York")
3. Once the search results appear, click on the Google Maps to CSV extension icon in your browser toolbar
4. Click the "Scrape Google Maps" button in the popup
5. After scraping is complete, review the data in the table 
6. Enter a filename (optional) and click "Download as CSV"
7. The data will be downloaded as a CSV file that you can open in Excel, Google Sheets, or other spreadsheet applications

## For Developers

### Setting Up Development Environment

#### Prerequisites
- [Visual Studio Code](https://code.visualstudio.com/download) (or your preferred code editor)
- [Node.js](https://nodejs.org/) (optional, for potential future development with npm packages)
- [Git](https://git-scm.com/downloads) (optional, for version control)
- Google Chrome browser

#### Clone the Repository
```bash
git clone https://github.com/user/google-maps-to-csv.git
cd google-maps-to-csv
```

#### Open in VS Code
```bash
code .
```

#### Setting up for Chrome Extension Development
1. In Chrome, navigate to `chrome://extensions/`
2. Enable "Developer mode" using the toggle in the top-right corner
3. Click "Load unpacked"
4. Browse to your project folder and select it
5. The extension should now appear in your extensions list

### Project Structure
```
google-maps-to-csv/
├── manifest.json       # Extension configuration
├── popup.html          # Extension popup interface
├── popup.js            # JavaScript for popup functionality
├── map.png             # Extension icon
└── README.md           # This documentation
```

### Making Changes

1. Edit the files in VS Code or your preferred editor
2. After making changes:
   - Navigate to `chrome://extensions/` in Chrome
   - Find the "Google Maps to CSV" extension
   - Click the refresh icon to reload the extension with your changes
3. Test your changes by using the extension

### Packaging for Distribution

To create a distributable version of your extension:

1. Make sure all files are updated and working correctly
2. Create a ZIP file containing all necessary files:
   - manifest.json
   - popup.html
   - popup.js
   - map.png
   - Any other required files
3. The ZIP file can be:
   - Uploaded to the Chrome Web Store (requires developer account)
   - Distributed for manual installation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Built by [CCwithAI](https://www.ccwithai.com)
