1. Use a Set to track values that have been seen. If a value is found in the set, immediately return false in that the string chars are not unique.

2. Use a frequency counter to count the char frequency in str1 and str2. Iterate over the freq in str1 and check the frequency against the freq of str2. Do the same for freq2.

3. Trim the string of white space. Split the string by whitespace and join by "%20".

OR: Use a regex to replace the whitespace with "%20"
The regex would be /(?<=\w)\s(?=\w)/g

4. Create a frequency counter to track the freq of each char. If the freq of each char except at most one, is 2, return true. Otherwise, return false. 

5. Create an index matcher object to hold each char and its index in both strings. Iterate over each index. For each different value at the specific index, increment the difference count by 1. If the diffCount is greater than 1, return false. Otherwise, return true

6. Use a regex to find the different parts where we have the same chars in a row and put them into an array. For each element of the array, combine the first char of that element with the length of that element and add it to a new string. Check to see if that new string length is less than the old one and return based off of that.
Regex: /([a-zA-Z])\1*/g
7. 

8. Create a copy of the input. Iterate over the original. If a 0 is found, turn the values in the copy in the same row and column to 0. Return the copy

9. Double the str2. Then, call isSubstring to check if str1 is found in that doubled str.

