# CY Smart Worksheet

## Upload to GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save and wait for GitHub to provide the Pages link.

## Main features

- Multiple worksheets
- Search and open saved worksheets
- IndexedDB browser storage
- Manual save and 10-second autosave
- Add rows and columns in bulk
- Paste cells copied from Excel
- SUM, AVERAGE, MIN, MAX and COUNT formulas by column
- Attachments
- Excel, CSV, PDF/Print and JSON export
- Light, dark and GME themes
- PWA installation and offline support after first visit

## Important storage note

Data is stored inside the browser and device used to open the GitHub Pages site.  
Use **JSON Backup** to transfer a worksheet to another device or browser.

## Excel export note

Excel export loads SheetJS from a public CDN. The first Excel export requires internet access.


## Excel export naming

- Excel filename: `Title_Company Name.xlsx`
- Excel worksheet tab: the worksheet `Title`
- Excel automatically limits worksheet tab names to 31 characters. Invalid tab characters are removed.
