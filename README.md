# Certificate Automator

A utility tool for bulk certificate generation developed for IT Circle at KhCE.

## Overview

Certificate Automator allows users to upload a PDF certificate template and a CSV file containing participant names, then automatically generates personalized certificates for each participant. The tool provides a visual interface for positioning and styling text on the certificate template.

## Features

- PDF template upload and preview
- CSV-based participant name import
- Visual text positioning with drag-and-drop interface
- Font customization (Helvetica, Times New Roman, Courier, Great Vibes)
- Text alignment options (left, center, right)
- Font size and color customization
- Bulk PDF generation and download

## Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`

3. Upload your certificate template (PDF format)

4. Upload a CSV file with participant names in the first column

5. Position and customize the text using the visual editor

6. Click "Generate PDF" to download the certificate bundle

## CSV Format

The CSV file should contain participant names in the first column. Headers are automatically skipped if detected.

Example:
```
Name
John Doe
Jane Smith
Robert Johnson
```

## Build for Production

```bash
npm run build
npm start
```

## Technical Stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- pdf-lib for PDF generation
- React PDF for preview
- Papaparse for CSV handling

## Developed By

IT Circle, Khwopa College of Engineering
