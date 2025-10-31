# LeetCode 1 - two sum

![Result Screenshot](1_two_sum.png)
### Personal Reflection

I think this problem shows how important it is to be able to quickly find the elements that satisfy certain conditions.
In this case, the problem asks us to find two numbers in an array that add up to a given target number.
To solve this problem, we can use a map to keep track of the sum of each possible combination of two numbers from the array.
Once we have calculated the sum of each possible combination of two numbers from the array using the map, we can iterate through all possible combinations of two numbers from the array using nested for loops.
For each possible combination of two numbers from the array that is being iterated through using the nested for loops, we can calculate the sum of the corresponding elements in the original array using the map.
Once we have calculated the sum of each possible combination of two numbers from the array using the map and have iterated through all possible combinations of two numbers from the array using nested for loops, we can return a list containing the indices of the two numbers that add up to the given target number in the original array.