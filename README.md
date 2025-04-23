# X12 834 File Viewer

A simple and effective web-based viewer for X12 834 EDI files — built with plain HTML, CSS, and JavaScript. This tool allows you to paste the raw 834 content into a text area and visually review each segment in a readable, color-coded table format.

---

## 🚀 Features

- ✅ **Paste-and-Parse**: Just paste your X12 834 file into the text area and click "Parse File".
- 🎨 **Color-Coded Segments**: Common segments like `INS`, `NM1`, `REF`, and `DTP` are color-coded for easy scanning.
- 🔍 **Segment & Element Breakdown**: Each segment is split and displayed with its elements listed for quick comprehension.
- 💡 **Zero Dependencies**: No libraries or frameworks required. Pure HTML + JavaScript.

---

## 📸 Screenshot

![834 Viewer Screenshot](screenshot.png) <!-- Replace or remove this line if you don't have a screenshot -->

---

## 📂 How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Paste the contents of your 834 file into the input box.
4. Click **"Parse File"** and view the output below.

---

## 🧠 Segment Color Legend

| Segment ID | Meaning              | Color        |
|------------|----------------------|--------------|
| `INS`      | Member Insurance     | Light Blue   |
| `REF`      | Reference Info       | Light Green  |
| `NM1`      | Individual Name      | Light Yellow |
| `PER`      | Contact Information  | Light Pink   |
| `DTP`      | Date or Time Period  | Khaki        |
| `N3`, `N4` | Address Info         | Lavender     |
| `HD`       | Health Coverage      | Light Red    |
| `SE`, `ST`, `BGN`, etc. | Misc/Headers | Light Gray   |

---

## ✏️ Customization

Want to color-code more segments or add tooltips? Open `index.html` and modify the CSS styles or JavaScript logic in the `parseX12()` function.

---

## 📄 License

MIT License. Use it, modify it, share it. Contributions welcome!

---
