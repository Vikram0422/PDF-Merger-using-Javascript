# PDF Merger

This JavaScript project allows you to merge two PDF files into a single PDF using a web interface. The project utilizes Express, Multer, and the pdf-merger-js library.

## Features

- **PDF Merging:**
  - Merge two PDF files into a single PDF document.

- **Web Interface:**
  - Provides a simple web interface for users to upload PDF files and trigger the merging process.

- **Responsive Design:**
  - Utilizes Bootstrap for a responsive and user-friendly layout.

## Implementation

The project consists of the following components:

- **Server (`server.js`):**
  - Express server handling file uploads and merging requests.
  - Serves the web interface.

- **PDF Merging Logic (`merge.js`):**
  - Utilizes the `pdf-merger-js` library to merge two PDF files.
  - Saves the merged PDF in the `public` directory.

- **Frontend (`index.html`):**
  - Bootstrap-based HTML file providing a user-friendly form to upload PDF files.


