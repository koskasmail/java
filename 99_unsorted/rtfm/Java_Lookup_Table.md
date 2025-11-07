<a name="topage"></a>

# Java Lookup Table

#### **A Java lookup table is a data structure used to map input values to corresponding output values efficiently, often in constant time.** It’s commonly implemented using arrays or maps like `HashMap`.
---

### 🔍 What Is a Lookup Table in Java?

A **lookup table** stores predefined mappings between keys and values. Instead of computing results dynamically, you retrieve them from the table, which improves performance and simplifies code. This is especially useful for:

- Replacing complex `if-else` or `switch` statements
- Speeding up repetitive calculations
- Organizing configuration or mapping data

---

### 🧠 Common Implementations

#### 1. **Using Arrays**
Best for integer-based keys with a fixed range.

```java
int[] squareLookup = new int[11];
for (int i = 0; i <= 10; i++) {
    squareLookup[i] = i * i;
}
System.out.println(squareLookup[5]); // Output: 25
```

#### 2. **Using HashMap**
Ideal for non-integer or sparse keys.

```java
Map<String, String> countryCodes = new HashMap<>();
countryCodes.put("US", "United States");
countryCodes.put("IL", "Israel");
System.out.println(countryCodes.get("IL")); // Output: Israel
```

#### 3. **Using EnumMap**
Efficient for enum keys.

```java
enum Status { OK, ERROR, UNKNOWN }

EnumMap<Status, String> statusMessages = new EnumMap<>(Status.class);
statusMessages.put(Status.OK, "All good");
statusMessages.put(Status.ERROR, "Something went wrong");
System.out.println(statusMessages.get(Status.ERROR)); // Output: Something went wrong
```

---

### 🧩 Use Cases

- **Color mapping** in image processing
- **Command routing** in CLI tools
- **Configuration settings** in apps
- **Caching** expensive computations

----

<p align="right">(<a href="#topage">back to top</a>)</p>
<br/>
<br/>
