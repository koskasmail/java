<a name="topage"></a>

# 00_signs_in_language

### 🔣 Common Java Symbols and Their Usage

| Symbol | Name                  | Usage Example                          | Description |
|--------|-----------------------|----------------------------------------|-------------|
| `;`    | Semicolon             | `int x = 5;`                           | Ends a statement |
| `{}`   | Curly Braces          | `{ int x = 5; }`                       | Defines blocks (methods, loops, classes) |
| `()`   | Parentheses           | `System.out.println("Hello");`         | Used in method calls and control flow |
| `[]`   | Square Brackets       | `int[] nums = {1, 2, 3};`              | Declares arrays |
| `.`    | Dot                   | `object.method()`                      | Accesses members of a class |
| `,`    | Comma                 | `int a = 1, b = 2;`                    | Separates variables or arguments |
| `=`    | Assignment Operator   | `x = 10;`                              | Assigns value to variable |
| `==`   | Equality Operator     | `if (x == 10)`                         | Compares values |
| `!=`   | Not Equal             | `if (x != 10)`                         | Checks inequality |
| `>`    | Greater Than          | `if (x > 5)`                           | Comparison |
| `<`    | Less Than             | `if (x < 5)`                           | Comparison |
| `>=`   | Greater or Equal      | `if (x >= 5)`                          | Comparison |
| `<=`   | Less or Equal         | `if (x <= 5)`                          | Comparison |
| `+`    | Addition / Concatenation | `x + y` or `"Hello " + name`        | Math or string joining |
| `-`    | Subtraction           | `x - y`                                | Math |
| `*`    | Multiplication/Asterisk        | `x * y`                       | Math |
| `/`    | Division              | `x / y`                                | Math |
| `%`    | Modulo                | `x % y`                                | Remainder |
| `++`   | Increment             | `x++`                                  | Adds 1 to variable |
| `--`   | Decrement             | `x--`                                  | Subtracts 1 from variable |
| `:`    | Colon                 | `case 1:`                              | Used in switch-case |
| `?`    | Ternary Operator      | `x > 5 ? "yes" : "no"`                 | Conditional expression |
| `"`    | Double Quotes         | `"Hello"`                              | String literals |
| `'`    | Single Quote          | `'A'`                                  | Character literals |
| `\\`   | Backslash             | `"\\n"`                                | Escape sequences |
| `@`    | Annotation Marker     | `@Override`                            | Metadata for classes/methods |

---

### Logical Operators

* `&&`   |   Logical AND   |   `if (x > 0 && y > 0)`   |   Combines conditions   |
* `||`   |   Logical OR    |   `if (x > 0 || y > 0)`   |   Combines conditions   |
* `!`    |   Logical NOT   |   `if (!isReady)`         |   Negates condition     |

---

### 🧮 Java Bitwise Operators


*  `&`    |  Bitwise AND           |  Sets each bit to 1 if both bits are 1                                        | `5 & 3` → `1`                |
*  `|`    |  Bitwise OR            |  Sets each bit to 1 if at least one bit is 1                                  | `5 | 3` → `7`                |
*  `^`    |  Bitwise XOR           |  Sets each bit to 1 if only one of the bits is 1                              | `5 ^ 3` → `6`                |
*  `~`    |  Bitwise NOT/tilde     |  Inverts all the bits (1 becomes 0, and vice versa)                           | `~5` → `-6`                  |
*  `<<`   |  Left Shift            |  Shifts bits to the left (multiplies by 2 for each shift)                     | `5 << 1` → `10`              |
*  `>>`   |  Signed Right Shift    |  Shifts bits to the right, preserving the sign (divides by 2 for each shift)  | `-8 >> 1` → `-4`             |
*  `>>>`  |  Unsigned Right Shift  | Shifts bits to the right, filling leftmost bits with 0                        | `-8 >>> 1` → large positive  |

---

### 🔍 Quick Examples

```java
int a = 5;      // 0101
int b = 3;      // 0011

System.out.println(a & b);  // 0001 → 1
System.out.println(a | b);  // 0111 → 7
System.out.println(a ^ b);  // 0110 → 6
System.out.println(~a);     // Inverts → -6
System.out.println(a << 1); // 1010 → 10
System.out.println(a >> 1); // 0010 → 2
```

* more links
    * https://github.com/koskasmail/whatAmess/blob/main/dev/00_signs_in_language/java.md
