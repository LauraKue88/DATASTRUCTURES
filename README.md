Q1.md:
(i). Ignore Constants - This is because coefficients and lower end terms are irrelevant for large input sizes due to The growth rate of the function remains the same regardless of the coefficient.
 Examples are: O(2n)→O(n) and O(n+5)→O(n).
 
 (ii). Focus on the Dominant Term - This is because only the term with the highest growth rate matters since the larger values of n, lower-order terms become minimal.
Example : O(n2+n)→O(n2).

(iii). Iterative Loops - A single loop iterating n times is O(n).
Example: Nested loops multiply complexities depending on the number of iterations : O(n×n)→O(n2

(iv). Consecutive Operations Add - If operations run sequentially, add their complexities, then simplify.
   Example: O(n)+O(n2)→ simplified to :O(n2), (since n2 dominates)
   
(v). Recursive Calls Multiply - This is by analyzing recursive algorithms using recurrence relations. The recursion often leads to logarithmic or exponential complexity.
Example: A binary search splits input in half each time that results in O(logn) complexity.

Q2.md
(i) Memory Location - Arrays have a fixed memory allocation thus classified under static data structure whereas Linked lists allow room for memory expansion
thus classified under dynamic data structures.
(ii) Performance - Arrays in terms of access speed, fast access to elements by index is required directly O(1)  whereas linked list, sequential access
is required O(n)
(iii). Insertion and Deletion : In arrays, Insertions and deletions are infrequent and mostly at the end whereas Linked lists, Frequent insertions and 
deletions are needed, especially at the beginning or middle.
