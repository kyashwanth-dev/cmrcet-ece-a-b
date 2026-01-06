Dr. Aria Chen is an astronomer at the Jaipur Observatory who tracks meteor showers. She uses a grid-based visualization system to map the night sky, where each cell represents a sector of the sky. For her upcoming presentation, she needs to generate a right-aligned triangle pattern of stars (*) that represents the increasing intensity of meteor activity over consecutive nights.

Given an integer `n` representing the number of observation nights, help Dr. Aria generate a right-aligned triangle pattern where:

- The first row has 1 star (Night 1)  
- The second row has 2 stars (Night 2)  
- And so on, until row `n` has `n` stars  

Each row should be right-aligned, meaning shorter rows should have leading spaces to align with the longest row.

---

### **Input Format**

A single integer `n` (1 ≤ n ≤ 50) representing the number of observation nights.

---

### **Output Format**

Print `n` lines, where the i-th line contains `(n - i)` leading spaces followed by `i` stars (`*`).  
Each star should be separated by a single space, and leading spaces should account for proper right alignment.
