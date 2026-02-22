# File Packer Unpacker (Java CLI)

![Language](https://img.shields.io/badge/Language-Java-orange)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow)

A lightweight Java-based file archiver that packs multiple files into a single archive using a custom header structure and extracts them via a CLI interface.

---

## ✨ Highlights

- Custom file packing format using structured headers (FileName + FileSize).
- Binary file handling using `FileInputStream` and `FileOutputStream`.
- Extracts multiple files from a single packed archive.
- CLI-based interactive execution.
- Demonstrates low-level file handling and stream management concepts.
- Exception handling included.

---

## 🚀 Build & Run

```bash
# Compile
javac FilePackerUnpacker.java

# Run
java FilePackerUnpacker
