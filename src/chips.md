# Table of the chips

A table that describe the chips.

**⚠ This table is not finished ⚠**

| Chip name | Description | Input | Output |
| ----------- | ----------- | ----------- | ----------- |
| 0 to 1 Detector | A group of chips that can detect the nuber they are assign to. Output a 8-bit code that a 7 display segment can read | 1x 4-bit | 1x 8-bit |
| 10 entry 8-bit OR | 10 8-bit OR grouped together | 10x 8-bit | 1x 8-bit |
| X 8-bit Memory | A memory that as X octet of memory | 2x 8-bit, 3x 1-bit, If it's the 256 Memory it as one more 8-bit input | 1x 8-bit |
| 4 AND | 4 AND gates put together | 4x 1-bit | 1x 1-bit |
| 7 to 8 bit adder | A binary adder that takes 2 7-bit number and adds them together outputing a 8-bit number | 2x 8-bit (The last bit is not used) | 1x 8-bit, 8x 1-bit |
| 7 to 8 bit signed adder | The same as the 7 to 8 bit adder but as another bit for each number telling if it is negative or not. | 2x 8-bit (The last bit is not used), 2x 1-bit | 1x 8-bit, 9x 1-bit |
| 8 -bit OR | An OR gate that takes 8-bit input | 2x 8-bit | 1x 8-bit |
| 8-bit register | A register that stores a 8-bit number | 1x 8-bit, 4x 1-bit | 1x 8-bit |
| AND | A basic AND logic gate | 2x 1-bit | 1x 1-bit |
| Comparateur 1-bit | A chip that takes 2 bit and say if they are equal or if one is grater than the other | 2x 1-bit | 3x 1-bit |
| Comparateur 8-bit | A chip that takes 2 8-bit number and say if they are equal or if one is grater than the other | 2x 8-bit | 3x 1-bit |
| D Latch | A data latch that can store 1 bit | 2x 1-bit | 1x 1-bit |
