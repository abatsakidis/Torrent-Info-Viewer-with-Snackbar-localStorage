# Torrent Info Viewer with Snackbar & localStorage

A web app to parse and display detailed information from `.torrent` files directly in the browser.

---

## Features

- Upload or drag & drop `.torrent` files to view their metadata.
- Display torrent name, info hash, piece length, number of pieces, total size.
- Show magnet link with trackers.
- Expandable file tree for multi-file torrents.
- Copy magnet link or individual filenames to clipboard with notifications.
- Save torrent info to a text file.
- Persistent data saved in `localStorage` for quick reload.
- Clear `localStorage` button to reset saved data.
- Responsive, dark-themed interface with retro green-on-black style.
- Snackbar notifications for user feedback.

---

## How to Use

1. Upload a `.torrent` file or drag & drop it into the dropzone.
2. View torrent metadata and files.
3. Use buttons to copy magnet link or save info as a file.
4. Click filenames in the file tree to copy them individually.
5. Clear localStorage anytime with the "Clear localStorage" button.

---

## Technologies

- [bencode](https://www.npmjs.com/package/bencode) for parsing torrent files.
- [node-forge](https://github.com/digitalbazaar/forge) for SHA1 hashing.
- Vanilla JavaScript and modern browser APIs.
- CSS for styling and animations.

---

## Notes

- All parsing is done client-side, no data is sent to any server.
- Requires modern browsers with support for File API, Clipboard API, and ES modules.

---

## License

MIT License

---

Enjoy using the Torrent Info Viewer!  
If you find any issues or want to contribute, feel free to open an issue or pull request.
