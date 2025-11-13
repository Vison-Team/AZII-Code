# AZII Code 8-bit

The AZII Code 8-bit standard extends the 7-bit version to support a wider range of characters, including international letters, additional symbols, and special characters. Each character is represented by a unique numeric code in the range 11–255, fully compatible with binary conversion.

---

## Character Table (8-bit)

| Char | Decimal | Binary (8-bit) | Description |
|:----:|:--------:|:---------------:|:-------------|
| A | 11  | 00001011 | Uppercase A |
| B | 12  | 00001100 | Uppercase B |
| C | 13  | 00001101 | Uppercase C |
| D | 14  | 00001110 | Uppercase D |
| E | 15  | 00001111 | Uppercase E |
| F | 16  | 00010000 | Uppercase F |
| G | 17  | 00010001 | Uppercase G |
| H | 18  | 00010010 | Uppercase H |
| I | 19  | 00010011 | Uppercase I |
| J | 20  | 00010100 | Uppercase J |
| K | 21  | 00010101 | Uppercase K |
| L | 22  | 00010110 | Uppercase L |
| M | 23  | 00010111 | Uppercase M |
| N | 24  | 00011000 | Uppercase N |
| O | 25  | 00011001 | Uppercase O |
| P | 26  | 00011010 | Uppercase P |
| Q | 27  | 00011011 | Uppercase Q |
| R | 28  | 00011100 | Uppercase R |
| S | 29  | 00011101 | Uppercase S |
| T | 30  | 00011110 | Uppercase T |
| U | 31  | 00011111 | Uppercase U |
| V | 32  | 00100000 | Uppercase V |
| W | 33  | 00100001 | Uppercase W |
| X | 34  | 00100010 | Uppercase X |
| Y | 35  | 00100011 | Uppercase Y |
| Z | 36  | 00100100 | Uppercase Z |
| a | 37  | 00100101 | Lowercase a |
| b | 38  | 00100110 | Lowercase b |
| c | 39  | 00100111 | Lowercase c |
| d | 40  | 00101000 | Lowercase d |
| e | 41  | 00101001 | Lowercase e |
| f | 42  | 00101010 | Lowercase f |
| g | 43  | 00101011 | Lowercase g |
| h | 44  | 00101100 | Lowercase h |
| i | 45  | 00101101 | Lowercase i |
| j | 46  | 00101110 | Lowercase j |
| k | 47  | 00101111 | Lowercase k |
| l | 48  | 00110000 | Lowercase l |
| m | 49  | 00110001 | Lowercase m |
| n | 50  | 00110010 | Lowercase n |
| o | 51  | 00110011 | Lowercase o |
| p | 52  | 00110100 | Lowercase p |
| q | 53  | 00110101 | Lowercase q |
| r | 54  | 00110110 | Lowercase r |
| s | 55  | 00110111 | Lowercase s |
| t | 56  | 00111000 | Lowercase t |
| u | 57  | 00111001 | Lowercase u |
| v | 58  | 00111010 | Lowercase v |
| w | 59  | 00111011 | Lowercase w |
| x | 60  | 00111100 | Lowercase x |
| y | 61  | 00111101 | Lowercase y |
| z | 62  | 00111110 | Lowercase z |
| 0 | 63  | 00111111 | Digit 0 |
| 1 | 64  | 01000000 | Digit 1 |
| 2 | 65  | 01000001 | Digit 2 |
| 3 | 66  | 01000010 | Digit 3 |
| 4 | 67  | 01000011 | Digit 4 |
| 5 | 68  | 01000100 | Digit 5 |
| 6 | 69  | 01000101 | Digit 6 |
| 7 | 70  | 01000110 | Digit 7 |
| 8 | 71  | 01000111 | Digit 8 |
| 9 | 72  | 01001000 | Digit 9 |
|   | 73  | 01001001 | Space |
| . | 74  | 01001010 | Period |
| , | 75  | 01001011 | Comma |
| ! | 76  | 01001100 | Exclamation mark |
| ? | 77  | 01001101 | Question mark |
| : | 78  | 01001110 | Colon |
| ; | 79  | 01001111 | Semicolon |
| ( | 80  | 01010000 | Left parenthesis |
| ) | 81  | 01010001 | Right parenthesis |
| [ | 82  | 01010010 | Left bracket |
| ] | 83  | 01010011 | Right bracket |
| { | 84  | 01010100 | Left brace |
| } | 85  | 01010101 | Right brace |
| + | 86  | 01010110 | Plus |
| - | 87  | 01010111 | Minus |
| * | 88  | 01011000 | Asterisk |
| / | 89  | 01011001 | Slash |
| = | 90  | 01011010 | Equals |
| _ | 91  | 01011011 | Underscore |
| " | 92  | 01011100 | Double quote |
| ' | 93  | 01011101 | Apostrophe |
| < | 94  | 01011110 | Less than |
| > | 95  | 01011111 | Greater than |
| @ | 96  | 01100000 | At symbol |
| # | 97  | 01100001 | Hash |
| $ | 98  | 01100010 | Dollar |
| % | 99  | 01100011 | Percent |
| & | 100 | 01100100 | Ampersand |
| ä | 101 | 01100101 | Lowercase a with diaeresis |
| ö | 102 | 01100110 | Lowercase o with diaeresis |
| ü | 103 | 01100111 | Lowercase u with diaeresis |
| ß | 104 | 01101000 | Sharp s (eszett) |
| é | 105 | 01101001 | e with acute |
| è | 106 | 01101010 | e with grave |
| ç | 107 | 01101011 | c with cedilla |
| ñ | 108 | 01101100 | n with tilde |
| … | 109 | 01101101 | Ellipsis |
| © | 110 | 01101110 | Copyright |
| ® | 111 | 01101111 | Registered trademark |
| ™ | 112 | 01110000 | Trademark |
| € | 113 | 01110001 | Euro |
| £ | 114 | 01110010 | Pound |
| ¥ | 115 | 01110011 | Yen |
| † | 116 | 01110100 | Dagger |
| ‡ | 117 | 01110101 | Double dagger |
| • | 118 | 01110110 | Bullet |
| ° | 119 | 01110111 | Degree |
| ± | 120 | 01111000 | Plus-minus |
| ≤ | 121 | 01111001 | Less or equal |
| ≥ | 122 | 01111010 | Greater or equal |
| √ | 123 | 01111011 | Square root |
| ∞ | 124 | 01111100 | Infinity |
| ∑ | 125 | 01111101 | Summation |
| ∏ | 126 | 01111110 | Product |
| Ω | 127 | 01111111 | Omega |
| α | 128 | 10000000 | Greek alpha |
| β | 129 | 10000001 | Greek beta |
| γ | 130 | 10000010 | Greek gamma |
| δ | 131 | 10000011 | Greek delta |
| π | 132 | 10000100 | Greek pi |
| θ | 133 | 10000101 | Greek theta |
| λ | 134 | 10000110 | Greek lambda |
| μ | 135 | 10000111 | Greek mu |
| Σ | 136 | 10001000 | Greek Sigma |
| Φ | 137 | 10001001 | Greek Phi |
| Ψ | 138 | 10001010 | Greek Psi |
| Ω | 139 | 10001011 | Greek Omega |
| ą | 200 | 11001000 | Lowercase a with tail |
| ć | 201 | 11001001 | Lowercase c with acute |
| ę | 202 | 11001010 | Lowercase e with tail |
| ł | 203 | 11001011 | Lowercase l with stroke |
| ń | 204 | 11001100 | Lowercase n with acute |
| ó | 205 | 11001101 | Lowercase o with acute |
| ś | 206 | 11001110 | Lowercase s with acute |
| ź | 207 | 11001111 | Lowercase z with acute |
| ż | 208 | 11010000 | Lowercase z with dot above |

