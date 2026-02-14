# DICOM ReLink

A web-based DICOM annotation workstation for medical imaging. Load, view, and annotate medical images directly in your browser with full privacy - all files stay on your local machine.

## Features

- **Multi-planar Viewing**: Display DICOM series in three orthogonal planes (axial, sagittal, coronal)
- **Interactive Annotations**: Create rectangle, ellipse, polygon, and freehand annotations
- **Measurement Tools**: Measure length, angle, and ROI statistics
- **Crosshair Sync**: Synchronized crosshairs between all viewports
- **Window/Level**: Adjust image contrast and brightness
- **Local-First**: File System Access API for direct local file access - no cloud uploads
- **Browser-Based**: No installation required, runs entirely in the browser

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **UI Library**: React 18
- **Language**: TypeScript
- **DICOM Rendering**: cornerstone.js
- **UI Components**: shadcn/ui (Radix UI + Tailwind CSS)
- **State Management**: Zustand
- **Icons**: Lucide React
- **Styling**: Tailwind CSS
- **File Access**: File System Access API

## Prerequisites

- Node.js 18 or higher
- npm, yarn, or pnpm
- Modern browser (Chrome/Edge recommended for full File System Access API support)

## Installation

```bash
# Clone the repository
git clone https://github.com/AchlysLove/dicom-relink.git
cd dicom-relink

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
```

## Development

```bash
# Run the development server
npm run dev

# Open your browser and navigate to
# http://localhost:3000
```

## Project Structure

```
dicom-relink/
├── dicom.pen                    # Design file (Pencil format)
├── medical-imaging.html         # HTML prototype
├── docs/
│   └── plans/
│       └── 2025-02-14-dicom-viewer.md  # Implementation plan
├── CLAUDE.md                    # Project instructions
└── README.md                    # This file
```

## Current Status

- ✅ Visual design complete (Pencil)
- ✅ HTML prototype with styling
- ✅ Comprehensive implementation plan
- 🚧 Next.js project setup
- 🚧 DICOM rendering implementation
- 🚧 Annotation tools development

## Roadmap

- [ ] Set up Next.js 14 project with TypeScript
- [ ] Integrate cornerstone.js for DICOM rendering
- [ ] Build multi-planar viewer component
- [ ] Implement annotation tools
- [ ] Add state management with Zustand
- [ ] Create file import/export functionality
- [ ] Add window/level controls
- [ ] Implement crosshair synchronization

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

[Specify your license here - e.g., MIT, Apache 2.0, etc.]

## Acknowledgments

- [cornerstone.js](https://www.cornerstonejs.org/) - Medical imaging library
- [MONAI Label](https://monai.io/) - Medical open-source AI for imaging
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [Next.js](https://nextjs.org/) - React framework

## Contact

For questions or support, please open an issue on GitHub.

---

**Note**: This project is currently in the design and planning phase. The implementation plan is documented in [`docs/plans/2025-02-14-dicom-viewer.md`](docs/plans/2025-02-14-dicom-viewer.md).
