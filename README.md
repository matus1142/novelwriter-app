# Novel Writer (Web App)

**Novel Writer** is a browser-based web application for serious novel writing.  
It runs entirely on the client side — no backend, no server, no installation required.

Designed for writers who want:
- A structured chapter/file system
- Writing on realistic paper layouts (A4 / A5)
- Automatic saving and version history
- Character / location / item management
- Easy export and backup

---

## Features

### Project Tree
- Create **folders and files**
- Hierarchical tree structure
- Drag & Drop to organize chapters
- Rename and delete items
- Stored locally using IndexedDB
 - documents – Novel content (stored as pages)
 - versions – Version history
 - entities – Characters, locations, items
 - tree – Project structure

All data stays on your device.
---

### Writing Editor
- `contenteditable`-based editor
- Realistic **paper layout**
  - Supports A4 and A5
- Automatic page splitting
- Page numbers
- Light / Dark theme
- Fully responsive (desktop & mobile)

---

### Line Numbers & Word Count
- Toggle line numbers on/off
- Real-time word count
- Page count tracking

---

### Dialogue Highlighting
- Automatically detects dialogue:
  - `"..."` or `'...'`
- Highlights dialogue text for better readability

---

### Entity System (Story Data)
Manage important story elements:
- Characters
- Locations
- Items
- Other custom entities

**Usage**
- Type `@name` inside the editor
- Autocomplete suggestions appear
- Select using:
  - Mouse
- Type >> for indent

Entities are rendered as linked references inside the text.

---

### Auto Save & Versioning
- Automatic saving while typing
- Manual version snapshots
- Version history per document
- Visual diff comparison
- Restore previous versions anytime

---

### Export & Import
- Export to **PDF**
- Export full project as **JSON**
- Import JSON backup to restore everything

---

### OneDrive Workflow (Manual Sync)
No API login required.

Suggested workflow:
1. Export project as JSON
2. Save the file to a `NovelWriter` folder in OneDrive
3. Import the file on another device when needed

---

## Tech Stack

- HTML5
- CSS3 (Responsive + Dark Mode)
- Vanilla JavaScript
- IndexedDB (Local Storage)
- jsPDF
- html2canvas

❌ No backend  
❌ No framework  
❌ No server dependency  

---

## How to Use

1. Clone or download this repository
   ```bash
   git clone https://github.com/yourname/novel-writer.git
   docker compose build
   docker compose up -d
   http://localhost:3006
2. Used via github at link: [novelwriter-app](https://matus1142.github.io/novelwriter-app/)


