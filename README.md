# JS-04--Arrays_and_Loops

JS-04 - Arrays and Loops Bryan Tevillo Betancourt ejercicios de arrays y ciclos 11/01/2024

## Deliverable:

A link to a Github repo where the exercises are resolved with JavaScript

Sum of Resistors in Series

Calculate the sum of all resistors connected in series.
Examples:

-   `sumResitance([-1,5,6,3])` should return `"15 ohms"`. (|−1| + 5 + 6 + 3 = 15)
-   `sumResitance([14,3.5,6])` should return `'23.5 ohms'`. (14 + 3.5 + 6 = 23.5)
-   `sumResitance([8,15,100])` should return `'123 ohms'`. (8 + 15 + 100 = 123)

Note: This approach uses the absolute value of each resistance to ensure all values are positive.

##Number divided into halves

## Given a number, return the number divided into its halves in an array.

Examples:

-   `numDiv(4)` should return `[2, 2]`.
-   `numDiv(10)` should return `[5, 5]`.

## Secret Society

Find the name of a secret society based on the first letter of each member's name.

Examples:

-   `secretName(["Esperanza", "Franco", "Nia"])` should return `'EFN'`.
-   `secretName(['Phoebe', 'Ross', 'Chandler', 'Joey', 'Monica', 'Rachel'])` should return `'CJMPRR'`.
-   `secretName(['Harry', 'Ron', 'Hermione'])` should return `'HHR'`.

## Online status

Display online status for a list of users.

Example:

-   `onlineStatus(['mockIng99', 'J0eyPunch', 'glassedFer'])` should return `'mockIng99, J0eyPunch and 1 more online'`.

## Array of Multiples

Create a function that takes two parameters (number, length) and returns an array of length containing multiples of the number.

Examples:

-   `arrayMultiplos(2, 10)` should return `[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]`.
-   `arrayMultiplos(17, 6)` should return `[17, 34, 51, 68, 85, 102]`.

## Positive dominance in Array

Write a function to determine if an array is positively dominant.
An array is positively dominant when the majority of its elements are positive.

Example:

-   `positiveDom([-1, -3, -5, 4, 6767])` should return `false`.

## Antipodal Average

Given an array, return a shorter array following these steps:

-   Split the array into two equal parts\*. If unequal, remove the middle element to obtain two equal arrays.
-   Sum each number of the first part with the inverse numbers of the second part.
-   Divide each number of the resulting array by 2.

Example:

-   For the array `[1,2,3,5,22,6]`, the result should be `[3.5, 12, 4]`.
