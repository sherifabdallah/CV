## AltaCV: LaTeX CV/Resume Class

**Version:** 1.7 (9 Aug 2023)  
**Author:** Sherif Abdullah  
**Contact:** sherif.abdullah.dev@gmail.com

### Overview

AltaCV is a LaTeX class for creating professional CVs and résumés. It was inspired by a résumé of Marissa Mayer created by Business Insider using enhancv.com. The project aims to provide a customizable template for users to create their own CVs efficiently.

### Features

- Clean and professional design
- Customizable layout and styling
- Supports multiple photos and right sidebar contents
- Clickable hyperlinks for personal info fields
- Compatible with pdflatex, XeLaTeX, and LuaLaTeX
- Uses popular fonts like Lato and Roboto Slab
- Configurable colors, fonts, and icons

### Requirements and Compilation

To compile a document using AltaCV, you need:

- pdflatex + biber + pdflatex
- `fontawesome5` package
- Lato and Roboto Slab fonts
- `ragged2e` package for better text alignment
- `paracol` package for multi-column layout

### Usage

- Use `\cvsection` with optional argument to insert right sidebar contents
- Compile with appropriate LaTeX engine (pdflatex, XeLaTeX, LuaLaTeX)
- Customize colors, fonts, and icons as needed

### Sample Files

- `sample.tex`: Default sample LaTeX file demonstrating usage
- `sample-old.tex`: Original sample template file (for historical record only)

### Additional Notes

- AltaCV is designed to be ATS-friendly, but actual compatibility may vary
- Use `\printinfo` or `\NewInfoField` to add custom information fields
- Configurable colors, fonts, and icons are provided for easy customization

For detailed usage instructions and customization options, refer to the documentation in the source files.

