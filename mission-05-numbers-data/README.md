# Mission 5 - Numbers and data

## Task 5.1 - Convert numbers by hand

| Question | My working and answer |
|---|---|
| Decimal 13 to binary | 13 ÷ 2 = 6 remainder 1; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading remainders from bottom to top: **1101**. |
| Decimal 25 to binary | 25 ÷ 2 = 12 remainder 1; 12 ÷ 2 = 6 remainder 0; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading remainders from bottom to top: **11001**. |
| Binary 1010 to decimal | (1 × 8) + (0 × 4) + (1 × 2) + (0 × 1) = 8 + 0 + 2 + 0 = **10**. |
| Binary 1101 to decimal | (1 × 8) + (1 × 4) + (0 × 2) + (1 × 1) = 8 + 4 + 0 + 1 = **13**. |
| Hexadecimal A to decimal | 10 * 1. Answer: **10**. |
| Hexadecimal 1F to decimal | (1 × 16) + (15 × 1) = 16 + 15 = **31**. |
| Binary 1111 to hexadecimal | 1111 in binary = 8 + 4 + 2 + 1 = 15. In hexadecimal, 15 = **F**. |

## Task 5.2 - Verify using Python

| Expression tested | Result | Matches my manual answer? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int("1010", 2)` | `10` | Yes |
| `int("1101", 2)` | `13` | Yes |
| `hex(25)` | `0x19` | Yes |
| `hex(31)` | `0x1f` | Yes |
| `int("A", 16)` | `10` | Yes |
| `int("1F", 16)` | `31` | Yes |
| `hex(15)` | `0xf` | Yes |

## Task 5.3 - Build a small number calculator
| Test number | Binary output | Hexadecimal output |
|---|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 84 | 0b1010100 | 0x54 |

- `bin()` converts a decimal number into binary, and `hex()` converts it into hexadecimal. `0b` shows that the number is in binary, and `0x` shows that it is in hexadecimal.

- First, the program asks me to enter a number. Then, `int()` changes the entered text into a whole number. After that, `bin()` and `hex()` convert the number. Finally, `print()` displays both results.

## Task 5.4 - How is text stored?
- **ASCII codes:** The ASCII code for `A` is 65 and for `a` is 97. I noticed that lowercase `a` is 32 numbers higher than uppercase `A`.

- **Why an encoding standard is needed:** Computers store everything as numbers, so they need a common rule to understand which number represents which letter. This helps different computers understand the same text.

- **One character not in basic ASCII:** ₹ (Indian Rupee symbol).

- What I Understood: I also learned that `bin()` converts numbers into binary and `hex()` converts them into hexadecimal. I understood that text encoding helps computers identify letters and symbols using numbers.

- Difficulty Faced: Initially, I found it confusing to convert numbers between different number systems, especially binary and hexadecimal. 





