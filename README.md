Easy 1
Given a string s consisting of words and spaces, return the length of the last word in the string.

This program first removes spaces, then checks if the string is empty. If the string is empty, it means sentence is not provided. If there is  only one word, it returns the length of the word as output. Otherwise, it finds the last space, the length of the word after it is calculated. Prints the last word and length.

Medium 2 
Given an integer array of size n, find all elements that appear more than ⌊ n/3 ⌋ times.

In this p[rogram it creates a dictionary to store the element and the number of counts. It calculates the threshold value, n/3, for element occurrence. Then iterates through the array, updating the element count in the dictionary. It then iterates through the dictionary again, checking if any element count exceeds the threshold. If an element count exceeds the threshold, it is added to a list of eligible elements. At last the program returns the list containing elements appearing more than n/3 times.

Hard 3
Given an integer n, count the total number of digit 1 appearing in all non-negative integers less than or equal to n.

First in the program it declare up variables digit place value (d), the total count of 1 found (ans), current count of 1 in the current digit position (c), the current digit itself (present), and the remaining digits after removing the current 1 (back). It Iterates through each digit of a non-negative integer, right to left. Then analyzes each digit: adds 1 count to total based on the position and value. Then accounts for zeros and other digits. Updates 1 count for current digit position.
Finally, returns total count of 1 found.

Easy 3
Given an integer numRows, return the first numRows of Pascal's triangle.

This program utilizes a nested list structure, where each sublist represents a single row of the triangle. The create function iterates through the given number of rows, building each subsequent row based on the values in the previous row. For each element in the current row, the program adds the corresponding elements from the previous row to determine its sum. At last, the entire triangle is returned and printed line by line for easy understanding.
