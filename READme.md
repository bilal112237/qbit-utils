# qbit-utils

A lightweight bitwise, permission-flag, and XOR/checksum utility library written in the Quantum programming language (`.sa`).

## Features
- **Bitwise Flags (`src/bitwise.sa`):** `has_flag`, `set_flag`, `clear_flag`, `toggle_flag`, `is_even`, `is_power_of_two`
- **XOR & Hashing (`src/cipher.sa`):** `xor_value`, `simple_hash`, `mix_keys`
- **Demo Runner (`main.sa`):** Verifies all core operations

## Usage
Run the demo with the Quantum compiler:
```bash
quantum main.sa