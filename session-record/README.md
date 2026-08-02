# TPM Session Record

A standalone live session journal for The Preston Method.

## GitHub Pages setup

1. Create a folder in the repository, for example `session-record`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` into that folder.
3. Commit the files.
4. Open the GitHub Pages URL for the folder, such as:
   `https://yourname.github.io/your-repository/session-record/`

## Data storage

Version 1 stores client and session records in the browser's local storage on the device being used.

Use **Data → Export Backup** regularly. To move to another device, export the JSON backup and import it on the second device.

Automatic multi-device synchronization requires a secure cloud database and is not included in this static version.

## Current features

- Searchable client list
- New clients and editable client notes
- Chronological session history
- Live exercise entry with autosave
- Exercise autocomplete
- Repeat-last-session option
- Loads, sets, reps/time, and exercise notes
- Session opening and closing notes
- Quick previous-session review
- Printable session record
- JSON backup export/import
- Offline caching after first successful load
