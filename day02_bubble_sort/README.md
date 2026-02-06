Bubble Sort – Key Points 
🔹 What Bubble Sort does

Repeatedly compares adjacent elements

Swaps them if they are in the wrong order

After each pass, the largest unsorted element moves to the end

🔹 Loop Conditions (MOST IMPORTANT)

Outer Loop (n - 1 times)

Because after each pass, one element reaches its correct position

For n elements, at most n - 1 passes are required

Inner Loop (n - 1 - i times)

Last i elements are already sorted

No need to compare them again

Reduces unnecessary comparisons

🔹 Pseudocode logic

Fix elements from the end of the array

Shrink the unsorted part after each pass

🔹 Time Complexity (you can say this confidently)

Best Case: O(n²)
(with basic implementation)

Best Case (optimized with swap flag): O(n)
(already sorted array)

Average Case: O(n²)

Worst Case: O(n²)
(reverse sorted array)

🔹 Space Complexity

O(1)

Sorting is done in-place

No extra data structures used

🔹 Stability

Stable sort

Equal elements keep their original relative order

🔹 When to use Bubble Sort

Small datasets

Learning / teaching sorting concepts

Not recommended for large inputs