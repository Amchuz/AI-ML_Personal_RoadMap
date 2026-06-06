# DSA Patterns Cheatsheet

Add your own notes here as you solve each pattern.

## Arrays & Hashmaps
- Use a hashmap when you need O(1) lookup
- Frequency counter pattern: count occurrences with a dict

## Two Pointers
- Use when array is sorted or you need pairs
- Start/end pointers moving toward each other

## Sliding Window
- Fixed or variable size window
- Use when asked for subarray/substring with a condition

## Binary Search
- Use when array is sorted or answer has monotonic property
- Template: lo, hi = 0, len-1; while lo <= hi: mid = (lo+hi)//2

## Stack
- Use for matching brackets, next greater element, monotonic problems
- Think: "what do I need to remember from before?"

## Linked Lists
- Fast/slow pointer for cycle detection
- Dummy head node simplifies edge cases

## Trees
- DFS: recursion or explicit stack
- BFS: queue, level by level
- Know: inorder/preorder/postorder

## Graphs
- BFS for shortest path
- DFS for connected components, cycle detection
- Topological sort for dependency ordering

## Dynamic Programming
- Identify: overlapping subproblems + optimal substructure
- Start with brute force recursion, then memoize, then bottom-up

## Heaps
- Max/min in O(log n)
- Use for: K largest/smallest, merge K sorted, median stream

## Backtracking
- Template: choose → explore → unchoose
- Build solution incrementally, abandon if constraints violated
