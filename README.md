Easy 1
Given a string s consisting of words and spaces, return the length of the last word in the string.
This program first removes spaces, then checks if the string is empty. If the string is empty, it means sentence is not provided. If there is  only one word, it returns the length of the word as output. Otherwise, it finds the last space, the length of the word after it is calculated. Prints the last word and length.

Medium 2 
Given an integer array of size n, find all elements that appear more than ⌊ n/3 ⌋ times.
In this p[rogram it creates a dictionary to store the element and the number of counts. It calculates the threshold value, n/3, for element occurrence. Then iterates through the array, updating the element count in the dictionary. It then iterates through the dictionary again, checking if any element count exceeds the threshold. If an element count exceeds the threshold, it is added to a list of eligible elements. At last the program returns the list containing elements appearing more than n/3 times.
