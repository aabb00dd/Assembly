# Intel and ARM Assembly Code - School Project

Welcome to my GitHub repository for a school project where I developed code for both **Intel (x86)** and **ARM** architectures. This project showcases basic programs written in assembly language for each platform, created as part of a computer architecture or systems programming course.

## 🧠 About the Project

This repository includes:

- Intel x86 Assembly programs (likely using NASM or similar assembler)
- ARM Assembly programs (designed for ARM-based processors)
- Comments and documentation for better understanding
- Example use cases and outputs where applicable

The goal of this project was to learn and demonstrate:

- Low-level programming on different architectures
- Understanding CPU instruction sets
- Writing efficient and functional assembly code

## 📁 Structure

/intel/
- Contains x86 assembly files
- May include build/run scripts
/arm/
- Contains ARM assembly files
- May include Raspberry Pi or emulator setup info

markdown
Copy
Edit

## ⚙️ Requirements

Depending on the code, you might need:

- NASM (Netwide Assembler) or GAS for Intel code
- ARM toolchain or Raspberry Pi setup for ARM code
- QEMU (optional for emulation)
- Linux/macOS/WSL environment recommended

## 🚀 How to Run

Navigate to the corresponding folder (`/intel` or `/arm`) and follow the instructions in the README file inside each.

Example (for Intel NASM):

```bash
nasm -f elf64 program.asm
ld -o program program.o
./program
