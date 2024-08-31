---

# Fraction Addition

This Java program adds fractions given in a single string expression and returns the result in its simplest form. The input string contains a series of fractions, which may include both positive and negative numbers, separated by the `+` or `-` signs.

## How It Works

1. **Input Parsing**: The program uses a `Scanner` with a delimiter to parse the input string `expression` into individual fractions.
2. **Fraction Processing**: Each fraction is split into its numerator and denominator. The program then updates the overall numerator and denominator by calculating the least common multiple (LCM) of the current and new denominators.
3. **Greatest Common Divisor (GCD)**: After each addition, the result is simplified using the GCD of the numerator and denominator.
4. **Output**: The final result is a single fraction in its simplest form.

## Code Explanation

### `fractionAddition(String expression)`

This is the main method of the program. It takes an input string `expression` containing fractions to be added.

- **Parameters**: 
  - `expression`: A string representing a series of fractions (e.g., `"1/2+1/3-2/3"`).

- **Returns**: 
  - A string representing the result of adding all fractions in `expression` in the simplest form (e.g., `"1/6"`).

### `gcd(int a, int b)`

This method calculates the greatest common divisor (GCD) of two integers using the Euclidean algorithm.

- **Parameters**: 
  - `a`: An integer.
  - `b`: Another integer.

- **Returns**: 
  - The GCD of `a` and `b`.

## Example

```java
Solution solution = new Solution();
String result = solution.fractionAddition("1/3-1/2+1/6");
System.out.println(result); // Output: "1/6"
```

## Usage

To use this code:

1. **Compile** the Java file:
   ```bash
   javac Solution.java
   ```

2. **Run** the program with your input:
   ```bash
   java Solution
   ```

Make sure to replace `"1/3-1/2+1/6"` with your desired input.

## Notes

- The input expression must be formatted correctly with valid fractions separated by `+` or `-` signs.
- The program assumes valid input. Handling invalid inputs (like division by zero or malformed fractions) is not covered in this version.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

