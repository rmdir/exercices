# Various supports for exercices

## 8-Bit Visual Binary Adder

A visual educational tool designed for SysAdmin and Computer Science students to understand binary arithmetic, logic gates, and two's complement representation.

### Features

* **Interactive Switches:** Set bits for two 8-bit inputs (A and B).
* **Real-time LEDs:** 9-LED output (8 bits + 1 Carry/Overflow).
* **Translation Table:** Live conversion between Binary, Hexadecimal, and Decimal.
* **Sign Toggle:** Switch between Unsigned (0 to 255) and Signed (-128 to 127) modes.

### Deployment

You can use Dockerfile:
   ```bash
   docker build -t binary-adder .
   ```
