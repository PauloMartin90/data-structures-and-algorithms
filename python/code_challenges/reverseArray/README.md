# Reverse an Array
<!-- Description of the challenge -->
Write a function called reverseArray which takes an array as an argument. Without utilizing any of the built-in methods available to your language, return an array with elements in reversed order.

## Whiteboard Process
<!-- Embedded whiteboard image -->
![Alt text](../assets/white_board.jpeg)
![Alt text](../assets/white_board_1.jpeg)

## Approach & Efficiency
<!-- What approach did you take? Discuss Why. What is the Big O space/time for this approach? -->
I took the approach of utilizing space in this situation. I get a big O(1) in space by allocating 1 byte to store a new array variable. I get a O(N) in time because I am only using one iterative process. 

If the case were that space is non-existant I would then leverage on making a longer time process and get a O(1.5) in time and O(N) in space. This is how I would do it. Without changing the size of the array I would swap positions with the last and the first position in the array. I can not do this simeltaneously so I would leverage one variable to retain the value of the position as I move them back and forth. 