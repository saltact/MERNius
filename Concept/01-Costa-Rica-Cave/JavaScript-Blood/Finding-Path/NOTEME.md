# 🦇 Subject: [Topic Name, e.g., Array Methods (`map`, `filter`, `reduce`)]

> **Log Date:** [e.g., March 18, 2026]
> **Status:** [e.g., Experiment Successful / Still Mutating (Need more practice)]

## 🩸 The Blue Blood (Core Concepts)
*Write the absolute most important rules and definitions here in bullet points. Keep it brief.*
* **`map()`:** Transforms every element in an array and returns a *new* array. It does not mutate the original array.
* **`filter()`:** Returns a new array containing only elements that pass a specific condition (returns true).
* **`reduce()`:** Boils down an array into a single value (like a sum or an object).

## 🧬 DNA Splicing (Code Snippets)
*Paste the most useful code blocks you wrote or learned today so you can copy-paste them later.*

```javascript
// 1. The Map Mutation
const vampireBats = [1, 2, 3];
const mutatedBats = vampireBats.map(bat => bat * 2);
// Result: [2, 4, 6]

// 2. The Filter Serum
const bloodTypes = ['O-', 'A+', 'B-', 'O-'];
const pureBlood = bloodTypes.filter(type => type === 'O-');
// Result: ['O-', 'O-']