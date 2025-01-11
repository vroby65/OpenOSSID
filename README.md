# OpenOSSID

[online demo](https://vroby65.github.io/OpenOSSID/)

**OpenOSSID** is a lightweight, browser-based markdown note manager designed for privacy and simplicity. Your notes are stored locally on your device, ensuring they remain private and secure.

![OpenOSSID Screenshot](https://cdn-icons-png.flaticon.com/128/3273/3273518.png)

## Features

- **Markdown Support**: Write notes in markdown format and preview them instantly.
- **IndexedDB Storage**: Notes are now saved using IndexedDB for improved performance and scalability.
- **Tree View**: Organize your notes in a hierarchical structure with parent and child nodes.
- **Drag and Drop Resizable Sidebar**: Easily adjust the width of the tree view panel.
- **Drag and Drop Node Reorganization**: Reorder your notes using drag-and-drop functionality.
- **Export, Import, and Merge**: Save your notes as a JSON file, reload them, or merge multiple files.
- **Context Menu**: Right-click on nodes to add, rename, or delete them.
- **Direct Node Access**: Open specific nodes directly from a URL.
- **Rename Menu**: Easily rename nodes using the context menu.
- **Default Notes Loader**: Added functionality to load a `default.json` file from the same folder as `index.html` (commented out by default).

## Getting Started

### Prerequisites

To use OpenOSSID, all you need is a modern web browser with JavaScript enabled.

### How to Use

1. Clone this repository or download the `index.html` file:
   ```bash
   git clone https://github.com/yourusername/openossid.git
   cd openossid
   ```
2. Open `index.html` in your web browser.

3. Explore the interface:
   - Use the **Tree View** on the left to navigate, create, or delete notes.
   - Drag and drop nodes to reorganize your notes easily.
   - Click the **Edit** button to edit the selected note or **View** to save changes.
   - Use **Save** to export your notes as a JSON file.
   - Use **Load** to import previously saved notes.
   - Load the `default.json` file (if present in the same folder as `index.html`) to start with pre-defined notes.

4. Customize your notes using Markdown:
   - Create headings with `#`, `##`, or `###`.
   - Add bullet points, links, code blocks, and more.
   - Use the **Markdown Preview** feature to instantly see your formatted notes.

### Example Markdown

```markdown
# My First Note
Welcome to **OpenOSSID**!

## Features
- Local Storage
- Markdown Support
- Hierarchical Organization

## Code Example
```javascript
console.log("Hello, OpenOSSID!");
```
```

## Screenshots

![Tree View](https://cdn-icons-png.flaticon.com/128/3273/3273518.png)

## Contributing

Contributions are welcome! If you have suggestions or find bugs, feel free to:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy note-taking with **OpenOSSID**!
