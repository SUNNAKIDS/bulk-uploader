# SunnaKids Bulk Uploader Web Tool

A browser-based client-side tool to download Surahs (105–114) from `mp3quran.net`, dynamically generate track thumbnails, format, and upload audio content directly to a SunnaKids device on your local network.

🌐 **Live Website:** [https://sunnakids.github.io/bulk-uploader/](https://sunnakids.github.io/bulk-uploader/)

---

## Features
- **100% Client-Side:** Everything runs locally inside your browser (downloads, canvas thumbnail generation, and uploads). No backend or cloud server needed.
- **Surahs 105–114:** Fetches audio directly from `mp3quran.net`.
- **Dynamic Covers:** Generates 149×199 PNG cover artwork directly via HTML5 `<canvas>`.
- **Auto-Categorization:** Populates `quran`, `prophets`, `original_stories`, and `companions` categories.
- **Live Diagnostics:** Ping device, view upload progress, and check NAND health.

---

## Browser Setup Note (Mixed Content)
Because this site is served securely via HTTPS (`https://sunnakids.github.io/bulk-uploader/`), browsers may block requests to local HTTP IP addresses (`http://192.168.1.X`) by default under Mixed Content security policies.

If you encounter network errors when pinging or uploading:
1. Click the **tune / padlock icon** in your browser's address bar.
2. Select **Site settings**.
3. Set **Insecure content** to **Allow**.
4. Reload the page.
