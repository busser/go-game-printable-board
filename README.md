# 9x9 Go Board - Printable PDF

A real-size printable 9x9 Go board for beginner games and practice.

## Features

- **Real-size dimensions**: 18.0cm x 19.1cm board with official proportions
- **9x9 grid**: 81 intersection points for shorter games
- **Official measurements**: 22.50mm × 23.86mm spacing (22:23 ratio)
- **Coordinate labels**: A-J (no I) and 1-9 for easy reference
- **Center star point**: Traditional tengen marking
- **Print-ready**: Optimized for A4 paper with proper margins

## Quick Start

### [👉 Download PDF 👈](go-9x9-board.pdf)

Or generate it yourself:

```bash
make
```

## Requirements

- Google Chrome (for PDF generation)
- ImageMagick (for PNG preview, optional)

## Build Commands

```bash
# Generate both PDF and PNG
make

# Generate only PDF
make go-9x9-board.pdf

# Generate only PNG preview
make go-9x9-board.png

# Clean generated files
make clean
```

## Board Specifications

- **Size**: 9×9 lines (8×8 squares)
- **Line spacing**: 22.50mm × 23.86mm (22:23 ratio)
- **Grid line thickness**: 0.7mm
- **Border line thickness**: 1.5mm
- **Overall dimensions**: 18.0cm × 19.1cm
- **Star points**: Five points at positions (3,3), (3,7), (5,5), (7,3), (7,7)
- **Star point diameter**: 3.6mm
- **Margins**: 15.0mm left/right, ~54.1mm top/bottom
- **Coordinates**: A-J (excluding I) horizontally, 1-9 vertically

## Usage

1. Generate the PDF using `make`
2. Print on A4 paper at 100% scale (no scaling)
3. The board will be real-size and ready for gameplay with standard Go stones

## License

This project follows the same structure as the [go-game-record-form](../go-game-record-form) project.