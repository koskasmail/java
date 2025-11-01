<a name="topage"></a>

## 🧮 03_Java_Bitwise_Operators


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

----

<p align="right">(<a href="#topage">back to top</a>)</p>
<br/>
<br/>
