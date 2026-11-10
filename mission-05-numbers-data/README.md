# Mission 5: Numbers and Data

## 1. Task / objective

To convert decimal, binary and hexadecimal numbers by hand, verify the results with Python, build a small number converter, and explain how text is stored.

## 2. Work completed

I did seven manual conversions, checked them in Python, wrote and tested `number_converter.py`, and answered questions about ASCII and text encoding.

### Task 5.1: Convert Numbers by Hand

| Question | My working and answer |
|---|---|
| Decimal 13 to binary | 13 ÷ 2 = 6 remainder 1; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading remainders from bottom to top: **1101**. |
| Decimal 25 to binary | 25 ÷ 2 = 12 remainder 1; 12 ÷ 2 = 6 remainder 0; 6 ÷ 2 = 3 remainder 0; 3 ÷ 2 = 1 remainder 1; 1 ÷ 2 = 0 remainder 1. Reading remainders from bottom to top: **11001**. |
| Binary 1010 to decimal | (1 × 8) + (0 × 4) + (1 × 2) + (0 × 1) = 8 + 0 + 2 + 0 = **10**. |
| Binary 1101 to decimal | (1 × 8) + (1 × 4) + (0 × 2) + (1 × 1) = 8 + 4 + 0 + 1 = **13**. |
| Hexadecimal A to decimal | A = 10, so (10 × 1) = **10**. |
| Hexadecimal 1F to decimal | (1 × 16) + (15 × 1) = 16 + 15 = **31**. |
| Binary 1111 to hexadecimal | 1111 in binary = 8 + 4 + 2 + 1 = 15. In hexadecimal, 15 = **F**. |

### Task 5.2: Verify Using Python

| Expression tested | Result | Matches my manual answer? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int("1010", 2)` | `10` | Yes |
| `int("1101", 2)` | `13` | Yes |
| `hex(25)` | `0x19` | Correct (1 × 16 + 9 = 25), an extra check with no manual answer |
| `hex(31)` | `0x1f` | Yes, `1f` is the same value as my `1F` |
| `int("A", 16)` | `10` | Yes |
| `int("1F", 16)` | `31` | Yes |
| `hex(15)` | `0xf` | Yes, `f` is the same value as my `F` |

`int(text, base)` reads the text as a number in the given base (2 for binary, 16 for hexadecimal) and gives the decimal value.

### Task 5.3: Build a Small Number Converter

| Test number | Binary output | Hexadecimal output |
|---|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 84 | 0b1010100 | 0x54 |

- `bin()` converts a decimal number into binary, and `hex()` converts it into hexadecimal. `0b` shows that the number is in binary, and `0x` shows that it is in hexadecimal.
- First, the program asks me to enter a number. Then, `int()` changes the entered text into a whole number. After that, `bin()` and `hex()` convert the number. Finally, `print()` displays both results.

### Task 5.4: How Is Text Stored?

- **ASCII codes:** The ASCII code for `A` is 65 and for `a` is 97. I noticed that lowercase `a` is 32 numbers higher than uppercase `A`.
- **Why an encoding standard is needed:** Computers store everything as numbers, so they need a common rule to understand which number represents which letter. This helps different computers understand the same text.
- **One character not in basic ASCII:** ₹ (Indian Rupee symbol).

## 3. Commands / tools used

- `python3` – Opens the Python interactive prompt, and runs `number_converter.py`.
- `bin()` – Converts a decimal number to binary.
- `hex()` – Converts a decimal number to hexadecimal.
- `int(text, base)` – Converts text in binary or hexadecimal to a decimal number.
- `input()` – Asks the user to type a value.
- `print()` – Displays results on the screen.
- `ord()` – Gives the code number of a character.
- `git status`, `git add`, `git commit`, `git push` – Used to check, stage, save and upload my work.
- VS Code – Used to write `number_converter.py` and this README.

## 4. My understanding

I learned that `bin()` converts numbers into binary and `hex()` converts them into hexadecimal. I understood that text encoding helps computers identify letters and symbols using numbers.

## 5. Difficulties faced

Initially, I found it confusing to convert numbers between different number systems, especially binary and hexadecimal.

## 6. How I resolved them

I practised the division method and the place-value method by hand, then checked each answer with Python.

## 7. Evidence / files

- `mission-05-numbers-data/number_converter.py`
- `mission-05-numbers-data/README.md`

## 8. Commit details

- Commit message: `Build number converter and practise data representation`
- Status: Pushed to GitHub.