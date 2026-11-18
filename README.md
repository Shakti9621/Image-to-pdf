# Image to PDF Converter

A portable Windows desktop app that turns JPG, PNG, BMP, TIFF and WEBP images into PDF files.

## Build

Requires Rust (stable) with the MSVC toolchain on Windows.

    cargo build --release

The executable is written to `target\release\image-to-pdf.exe`.

## Portable release folder

1. Create a folder such as `ImageToPDF\`.
2. Copy `target\release\image-to-pdf.exe` into it.
3. Copy the folder to a USB drive or any location. No installer or registry entries are needed.

## Notes

- The app stores no settings or temporary files. Preferences reset when it closes.
- Existing PDF files are never replaced without asking.
