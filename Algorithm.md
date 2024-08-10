Sure! Here's a concise overview of key points related to asymptotic notation that you should remember for an MSc admission test:

### Key Points on Asymptotic Notation

1. **Big O Notation (`O`)**:
   - **Purpose**: Describes the worst-case upper bound of an algorithm's time or space complexity.
   - **Example**: \( O(n^2) \) means the algorithm's runtime grows at most quadratically with the input size.

2. **Omega Notation (`Ω`)**:
   - **Purpose**: Describes the best-case lower bound of an algorithm's time or space complexity.
   - **Example**: \( \Omega(n) \) means the algorithm's runtime is at least linear with the input size.

3. **Theta Notation (`Θ`)**:
   - **Purpose**: Describes a tight bound, meaning the algorithm's time or space complexity is both upper and lower bounded by the same function.
   - **Example**: \( \Theta(n \log n) \) means the runtime grows at exactly \( n \log n \).

4. **Little o Notation (`o`)**:
   - **Purpose**: Describes an upper bound that is not tight, meaning the algorithm grows slower than the given function.
   - **Example**: \( o(n^2) \) implies the runtime is less than quadratic, but not equal to \( O(n^2) \).

5. **Little Omega Notation (`ω`)**:
   - **Purpose**: Describes a lower bound that is not tight, meaning the algorithm grows faster than the given function.
   - **Example**: \( \omega(n) \) implies the runtime is greater than linear, but not exactly \( \Omega(n) \).

### Practical Examples:
- **Constant Time**: \( O(1) \) — e.g., accessing an array element.
- **Logarithmic Time**: \( O(\log n) \) — e.g., binary search.
- **Linear Time**: \( O(n) \) — e.g., iterating over an array.
- **Quadratic Time**: \( O(n^2) \) — e.g., bubble sort.

### Applications:
- **Comparing Algorithm Efficiency**: Helps in choosing the best algorithm for large inputs.
- **Scalability**: Important for understanding how algorithms behave as input size increases.

These key points will help you quickly recall the essentials of asymptotic notation during your MSc admission test. Good luck!
