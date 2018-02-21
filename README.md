## Why do you prefer JavaScript?
 * Loosely typed, type conversion.
 * ES6 adds a lot of syntactic sugar and removes former gripes about the language.
 * First class functions.
 * Allows for multiple paradigms (functional, oop, etc.)
 * With NodeJS and NoSql databases, it allows you to write a full stack application without having to witch languages/syntax

 ## Why would you choose a linked list over an array?
 * Can grow in size. Insertion and deletion are easily implemented. Constant-time (O(1)) insertions/deletions from the list. You dont need random access.

 ## What is recursion?
 * A recursive function is one that calls itself.
 * Alternative to iteration.
 * 2 Parts: function call and base case
 * As functions are invoked, they are added to the call stack. After the last is invoked they are returned off of the call stack in LIFO (Last In First Out) order.
 * Can use a helper method

## Memoization vs Tabulation
* Memoization cahces answers to previously solved problems. This can improve time/speed. With tabulation, all subproblems must be solved and the order is important. If you need to solve every subproblem, tabulation requires less overhead.

## What will happen if your recursive function doesn't have a base case?
* This will result in a stack overflow.

## Hash maps. How are they implemented in JS? Why would you choose to implement a hash table over other data structures?
* A hashmap, which is different than a hash table(using key hashes to lookup the corresponding value), is a mapping of key value pairs. In Javascript, this is implemented using an Object. A hashmap is efficient if we want to searching, adding, or deleting items based on a key value. Good if order doesn't matter.

## Big O Questions:
  * Adding to an array - O(1) or O(n) if you run out of space in the array.
  * Array access - always O(1)
  Operation | Runtime
  --------- | -------
  Accessing an element with an index | O(1)
  push / unshift | O(n)
  pop | O(1)
  find | O(n)
  remove (using splice) | O(n)

## Quicksort


## Binary Search

