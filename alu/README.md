# ALU Project for CSE224

This repository contains the full RTL design and OpenLane implementation for an 8-bit Arithmetic Logic Unit (ALU) project.

## 🔧 Features
- Inputs: 8-bit A, 8-bit B, 3-bit opcode
- Output: 8-bit result
- Supported operations:
  - NOT A
  - A OR B
  - A XOR B
  - A AND B
  - A * B
  - A + B
  - A - B
  - Default: 0

## 📁 Project Structure
```
- `src/`: Verilog source file  
- `config.json`: OpenLane configuration  
- `pin_order.cfg`: IO placement configuration  
- `runs/`: Complete run results (floorplan, placement, routing, etc.)
```

## 📦 Full Design Files
Click below to download the entire project including the `runs/` folder:

👉 [Download ALU Full Design (Google Drive)](https://drive.google.com/file/d/1W3c-zebwTO0BfJub_CXdtOzCPCFFN7m-/view?usp=share_link)
