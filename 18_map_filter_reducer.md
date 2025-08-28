https://www.youtube.com/watch?v=zdp0zrpKzIE&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=22

1. map method is used when we want transformation of whole array.
2. filter is used when we want to filter the arrar to obtain required value.
3. reduce is used when we want to reduce the array to single value eg (max, min, avg, sum, difference etc).
4. reduce passes two arguments one function(which includes accumulator and initial value as argument itself) and another initial value of accumulator.
   

| Method      | Callback Parameters (fixed order)                  | `initialValue`?          | Return Value                                        | Return Length               |
| ----------- | -------------------------------------------------- | ------------------------ | --------------------------------------------------- | --------------------------- |
| **forEach** | `(element, index, array)`                          | ❌ Not applicable         | **Always `undefined`** (used for side effects only) | N/A (does not build array)  |
| **map**     | `(element, index, array)`                          | ❌ Not applicable         | New array (each element = callback return)          | **Same length** as original |
| **filter**  | `(element, index, array)`                          | ❌ Not applicable         | New array (only elements passing condition)         | ≤ original length           |
| **reduce**  | `(accumulator, currentValue, currentIndex, array)` | ✅ Optional (recommended) | Any type (number / string / object / array / …)     | Usually **single value**    |

<img width="416" height="401" alt="Screenshot 2025-08-28 at 12 35 34 PM" src="https://github.com/user-attachments/assets/34e00e67-e91f-4b15-985d-27bf76164e6b" />

<img width="425" height="362" alt="Screenshot 2025-08-28 at 12 37 46 PM" src="https://github.com/user-attachments/assets/16ae31e5-68db-4fb4-b68b-5d99743ef3b6" />
