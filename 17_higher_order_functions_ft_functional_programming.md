https://www.youtube.com/watch?v=HkWxvB1RJq0&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=21

1. Follow DRY(Don't Repeat Yourself) principle while coding.
2. Use function to stop writing repeating line of codes.
3. Function that takes another function as argument(callback function) is known as Higher order functions.
4. It is this ability that function can be stored, passed and returned,  they are called first class citizens.
5. If we use Array.property.function-name. This function is accessible to any array in your code.

| Method      | Callback Parameters (fixed order)                  | `initialValue`?          | Return Value                                        | Return Length               |
| ----------- | -------------------------------------------------- | ------------------------ | --------------------------------------------------- | --------------------------- |
| **forEach** | `(element, index, array)`                          | ❌ Not applicable         | **Always `undefined`** (used for side effects only) | N/A (does not build array)  |
| **map**     | `(element, index, array)`                          | ❌ Not applicable         | New array (each element = callback return)          | **Same length** as original |
| **filter**  | `(element, index, array)`                          | ❌ Not applicable         | New array (only elements passing condition)         | ≤ original length           |
| **reduce**  | `(accumulator, currentValue, currentIndex, array)` | ✅ Optional (recommended) | Any type (number / string / object / array / …)     | Usually **single value**    |
