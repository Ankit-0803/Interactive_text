# Interactive Text Manipulation Inspired by Liquid Text

This project implements interactive text manipulation features inspired by Liquid Text, allowing users to dynamically manipulate text for better contextual understanding. The app is built with React and supports text manipulation, multi-page PDF navigation, and responsive design.

---

## Features

1. **Dynamic Text Spacing**
   - Two-finger pinch gesture to adjust the spacing between lines of text dynamically.
   - Smooth animations for seamless user interaction.

2. **Text Overlap for Contextual Comparison**
   - Select and drag lines of text to overlap for better contextual understanding.
   - Visual indicators for overlapping text ensure clarity.

3. **Multipage Document Navigation**
   - Upload and view multipage PDF documents.
   - Navigate seamlessly between pages while retaining text manipulation states.

4. **UI Reset**
   - Reset button to return the text layout and document states to their defaults.

5. **Responsive Design**
   - Works on both desktop and mobile devices.
   - Optimized for performance and scalability.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/interactive-text-manipulation.git
   cd interactive-text-manipulation
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

---

## Usage

1. **Dynamic Text Manipulation**
   - Click on text lines to select them.
   - Drag selected lines to overlap or adjust their positions.

2. **PDF Viewer**
   - Upload a PDF document using the file input.
   - Navigate between pages using the Next and Previous buttons.

3. **Reset Layout**
   - Click the "Reset Layout" button to reset text and document states.

---

## Project Structure

```
interactive-text-manipulation/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── TextManipulator.js
│   │   ├── PDFViewer.js
│   ├── styles/
│   │   ├── TextManipulator.css
│   │   ├── PDFViewer.css
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
└── README.md
```

---

## Dependencies

- React: ^19.0.0
- @use-gesture/react: ^10.3.1
- react-pdf: ^5.7.2
- react-scripts: 5.0.1

---
This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
