# employee-timesheet-enhance

## Manual Installation of the Chrome Extension (Load Unpacked)

This guide explains how to manually install the `employee-timesheet-enhance` Chrome extension using the "Load unpacked" method. This is useful for development, testing, or if you prefer not to install extensions from the Chrome Web Store.

**Prerequisites:**

*   You have the extension's source code (the directory containing the `manifest.json` file and other extension files).
*   You have Google Chrome installed on your computer.

**Steps:**

1.  **Open Chrome Extensions Page:**
    *   Open Google Chrome.
    *   In the address bar, type `chrome://extensions/` and press Enter.

2.  **Enable Developer Mode:**
    *   In the top right corner of the Extensions page, you'll see a toggle switch labeled "Developer mode."
    *   Click the toggle to turn Developer mode **ON**.

3.  **Load Unpacked Extension:**
    *   Once Developer mode is enabled, you'll see three new buttons appear: "Load unpacked," "Pack extension," and "Update."
    *   Click the **"Load unpacked"** button.

4.  **Select Extension Directory:**
    *   A file browser window will open.
    *   Navigate to the directory where you have the `employee-timesheet-enhance` extension's source code.
    *   **Important:** Select the **directory itself**, not any specific file within it. This directory should contain the `manifest.json` file.
    *   Click the **"Select Folder"** (or similar) button.

5.  **Extension Installed:**
    *   If the extension is valid (i.e., the `manifest.json` is correctly formatted and all required files are present), the `employee-timesheet-enhance` extension will now be installed and enabled in Chrome.
    *   You should see it listed on the `chrome://extensions/` page.

6. **Pin the Extension (Optional):**
    * To easily access the extension, click the puzzle piece icon (Extensions) in the Chrome toolbar.
    * Find the `employee-timesheet-enhance` extension in the list.
    * Click the pin icon next to it to pin it to your toolbar.

**Troubleshooting:**

*   **"Manifest file is missing or unreadable" error:**
    *   Double-check that the `manifest.json` file exists in the directory you selected.
    *   Ensure the `manifest.json` file is correctly formatted JSON. You can use a JSON validator online to check it.
*   **"Could not load extension" error:**
    *   This usually indicates an error in the `manifest.json` file or a missing required file.
    *   Carefully review the error message in Chrome for more details.
    *   Ensure all files referenced in the `manifest.json` are present in the selected directory.
* **Extension not showing up:**
    * Make sure you selected the folder that contains the manifest.json file and not a subfolder or a file.
    * Try restarting chrome.

**Updating the Extension:**

*   If you make changes to the extension's code, you'll need to update it in Chrome.
*   Go to `chrome://extensions/`.
*   Click the **"Update"** button in the top right corner. This will reload all unpacked extensions.
* Alternatively, you can disable and re-enable the extension.

By following these steps, you can successfully install and manage the `employee-timesheet-enhance` Chrome extension manually.

## How to use

Go to the "TIMESHEET" tab to see your much needed information. If it doesn't show up after 3 seconds, please refresh.