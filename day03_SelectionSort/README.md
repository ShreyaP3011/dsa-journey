#Loop logic explained (IMPORTANT)
    Outer loop (n - 1)
    Fixes one element per pass
Left side becomes sorted
    Inner loop (i + 1 to n)
    Searches for the minimum in the unsorted part

#Time & Space Complexity
| Case    | Time  |
| ------- | ----- |
| Best    | O(n²) |
| Average | O(n²) |
| Worst   | O(n²) |
Space: O(1) (in-place)
Swaps: Only n - 1 (better than Bubble Sort)

Can Selection Sort ever be O(n)? Why or why not?
❌ Short answer: NO
🔹 Why?
Selection Sort always scans the entire unsorted part, even if the array is already sorted.

