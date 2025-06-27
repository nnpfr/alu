# Table of the chips

A table that describe the chips.

**⚠ This table only contains the major chips ⚠**

| Chip name | Description | Input | Output |
| ----------- | ----------- | ----------- | ----------- |
| 0 to 9 Detector | A group of chips that can detect the number they are assign to. Output a 8-bit code that a 7 display segment can read | 1x 4-bit | 1x 8-bit |
| 10 entry 8-bit OR | 10 8-bit OR grouped together | 10x 8-bit | 1x 8-bit |
| 16 9-bit Memory | A memory that as 16x9-bit of memory | 2x 8-bit, 5x 1-bit | 1x 8-bit, 1x 1-bit |
| 259 9-bit Memory | A memory that as 256x9-bit of memory | 3x 8-bit, x3 1-bit | 1x 8-bit, 1x 1-bit |
| 4 AND | 4 AND logic gate put together | 4x 1-bit | 1x 1-bit |
| 7 to 8 bit adder | A binary adder that takes 2 7-bit number and adds them together outputing a 8-bit number | 2x 8-bit (The last bit is not used) | 1x 8-bit, 8x 1-bit |
| 7 to 8 bit signed adder | The same as the 7 to 8 bit adder but as another bit for each number telling if it is negative or not. | 2x 8-bit (The last bit is not used), 2x 1-bit | 1x 8-bit, 9x 1-bit |
| 8 -bit OR | An OR logic gate that takes 8-bit input | 2x 8-bit | 1x 8-bit |
| 9-bit register | A register that stores a 8-bit number and one more bit (generaly for the negative numbers) | 1x 8-bit, 5x 1-bit | 1x 8-bit, 1x 1-bit |
| AND | A basic AND logic gate | 2x 1-bit | 1x 1-bit |
| Comparateur 1-bit | A chip that takes 2 bit and say if they are equal or if one is grater than the other | 2x 1-bit | 3x 1-bit |
| Comparateur 8-bit | A chip that takes 2 8-bit number and say if they are equal or if one is grater than the other | 2x 8-bit | 3x 1-bit |
| D Latch | A data latch that can store 1 bit | 2x 1-bit | 1x 1-bit |
| XOR | A basic XOR logic gate | 2x 1-bit | 1x 1-bit |
| OR | A basic OR logic gate | 2x 1-bit | 1x 1-bit |
| NOT | A basic NOT logic gate | 1x 1-bit | 1x 1-bit |
| NAND | A basic NAND logic gate | 2x 1-bit | 1x 1-bit |
| NOR | A basic NOR logic gate | 2x 1-bit | 1x 1-bit |
| Number display | Get 3 digits to display on the 7 segment display, can also display a minus sign and get rid of extras zero | 3x 4-bit, 2x 1-bit | None |
| Number detector | A chip that get a 4-bit number and transform it into a 8-bit format that a 7 segment display can understand. It can also hide the zeros | 1x 4-bit, 1x 1-bit | 1x 8-bit, 1x 1-bit |
| Inverseur 8-bit | A chip that invert a 8-bit signal if the 1-bit entry is active | 1x 8-bit, 1x 1-bit | 1x 8-bit |
| Stopper | Stops the current of a 1-bit signal if another 1-bit signal is active | 2x 1-bit | 1x 1-bit |
| Stopper 8-bit | Does the same as a stopper but for a 8-bit entry | 1x 8-bit, 1x 1-bit | 1x 8-bit |
| DECODER 2-4 | Get 2 1-bit input and uses  it to turn one of it's output | 2x 1-bit | 4x 1-bit |
| 8-BIT 3 state buffer | A 3 state bufferfor 8-bit number | 1x 8-bit, 1x 1-bit | 1x 8-bit |
| DABBLE | A chip used in the Doubble Dabble Algorithm | 4x 1-bit | 4x 1-bit |
| Number decompositor | A chip that execute the Doubble Dabble Algorithm to decompose an 8-bit number into 3 4-bit number (Hundreds, Tens, Ones) | 1x 8-bit | 3x 4-bit |

---

### An image of all the chips

![An image of all the chips](https://github.com/nnpfr/alu/blob/main/images/chips.png?raw=true)


