# SIC Disassembler

This project implements a disassembler for the Simple Instructional Computer (SIC) architecture. It takes in machine/object code formatted in standard SIC records and outputs corresponding assembly-level instructions.

## 💡 What It Does

- Parses input SIC object code (e.g., `.obj` file or hexadecimal stream)
- Identifies text, header, and end records
- Decodes opcodes and operands to reconstruct SIC assembly instructions
- Outputs the human-readable assembly format

## 🧠 Why It Matters

Disassemblers are critical tools in reverse engineering, compilers, and malware analysis. This project shows a strong understanding of:
- Low-level instruction formats
- Opcode mapping
- Manual memory address tracking and label resolution

## 📂 Project Files

- `disassembler.py` – main disassembly logic
- `input.obj` – example object file input
- `README.md` – project documentation
- `requirements.txt` – libraries if used (e.g., for CLI UI or file handling)

## 🚀 How to Use

1. Place your SIC object file in the same folder.
2. Run the script:
   ```bash
   python disassembler.py input.obj
