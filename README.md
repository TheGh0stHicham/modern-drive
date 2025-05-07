# Modern Drive

A browser-based file management system with a clean, modern interface that provides drag-and-drop functionality, right-click context menus, and real-time file operations.

![Modern Drive Screenshot](https://i.ibb.co/9kSNrbs8/Screenshot-2025-05-07-200557.png)

## Features

- **Modern UI**: Clean, responsive interface with light theme
- **Drag and Drop**: Easily move files and folders or upload new content
- **Right-Click Context Menu**: Create folders, files, upload, and manage content
- **Dynamic File Icons**: Icons change based on file extension
- **File Preview**: Preview images, PDFs, text files, and more
- **Real-time Updates**: Instant refresh when files are created, uploaded, or moved
- **Storage Tracker**: Visual indicator of storage usage
- **Multiple View Modes**: Switch between grid and list views
- **Breadcrumb Navigation**: Easily navigate through folder structure

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3 with Tailwind CSS**: Styling and responsiveness
- **JavaScript**: Core functionality and interactions
- **jQuery**: DOM manipulation and event handling
- **SQLite.js**: Client-side database for file storage
- **Font Awesome**: Icons for files and UI elements
- **PDF.js**: PDF viewing capabilities

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No server requirements - runs entirely in the browser

### Installation

1. Clone the repository or download the source code:
   ```
   git clone https://github.com/TheGh0stHicham/modern-drive.git
   ```

2. Open the `index.html` file in your web browser.

That's it! The application runs entirely in your browser and uses client-side storage.

## Usage

### Basic Navigation

- **Navigate folders**: Double-click on folders to open them
- **Go back**: Use the breadcrumb navigation at the top
- **Change view**: Toggle between grid and list views using the buttons in the top right

### File Operations

- **Upload files**: 
  - Click the "Upload Files" button in the sidebar
  - Drag and drop files anywhere in the main area
  - Right-click and select "Upload"

- **Create new folder**:
  - Right-click on empty space and select "New Folder"
  - Enter a name for the folder

- **Create new file**:
  - Right-click on empty space and select "New File"
  - Enter a name with extension (e.g., "document.txt")

- **Open a file**:
  - Double-click on a file to open it in the preview mode

- **Move files/folders**:
  - Drag and drop items onto folders
  - Right-click, cut, then paste in the destination folder

- **Delete files/folders**:
  - Right-click on an item and select "Delete"

## Storage

Modern Drive uses the browser's IndexedDB (via SQLite.js) to store your files. This means:

- Files are stored locally in your browser
- Storage is limited to available browser storage
- Files aren't uploaded to any server
- Data persists between sessions on the same browser/device

## Known Limitations

- Maximum file size depends on your browser and device memory
- No sharing capabilities between users
- No cloud synchronization
- Limited file preview for certain formats
- Browser storage may be cleared when clearing browser data

## Future Improvements

- [ ] Dark theme option
- [ ] File sharing capabilities
- [ ] Cloud storage integration
- [ ] More advanced file operations (compression, etc.)
- [ ] Advanced search functionality
- [ ] Customizable UI
- [ ] Additional file previews for more formats
- [ ] Multi-select for bulk operations

## Security

Since Modern Drive runs entirely in your browser:
- Files never leave your device
- No server-side processing of your data
- Your files are as secure as your browser/device

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [jQuery](https://jquery.com/)
- [SQL.js](https://github.com/sql-js/sql.js/)
- [PDF.js](https://mozilla.github.io/pdf.js/)

---

Made with ❤️ by Your Hicham Ezzamzami
