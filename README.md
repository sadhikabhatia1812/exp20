AIM:
To implement and understand different searching techniques in C++, including Linear Search, Sequential Search, and Binary Search.

THEORY:
Searching is the process of finding the location of a specific element within a data set.

Linear Search: Checks each element of the array sequentially until the desired element is found or the end of the array is reached.
Sequential Search: Similar to linear search; elements are compared one by one from the beginning to the end.
Binary Search: Works on a sorted array. Repeatedly divides the array into halves and compares the middle element with the target until found.
🔹 Searching Algorithms:

Linear/Sequential Search – Simple search by checking elements one by one.
Binary Search – Efficient search on sorted arrays using divide-and-conquer.
⚙️ Algorithm:

Linear/Sequential Search:

Start from the first element of the array.
Compare the current element with the target.
If it matches, return the index.
If not, move to the next element and repeat until the end of the array.
If not found, return “Element not found”.
Binary Search:

Ensure the array is sorted.
Find the middle element of the array.
Compare the middle element with the target.
If equal, element found.
If target is smaller, repeat search in the left half.
If target is larger, repeat search in the right half.
Repeat until the element is found or the subarray size becomes zero.
Topics Covered:

Linear Search
Sequential Search
Binary Search
Searching in arrays
Divide-and-conquer technique (for binary search)
CONCLUSION:

Successfully implemented Linear, Sequential, and Binary Search algorithms in C++.
Understood the difference between simple search and efficient search.
Binary search is more efficient than linear/sequential search for sorted arrays.
