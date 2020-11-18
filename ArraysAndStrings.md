1. Use a Set to track values that have been seen. If a value is found in the set, immediately return false in that the string chars are not unique.

2. Use a frequency counter to count the char frequency in str1 and str2. Iterate over the freq in str1 and check the frequency against the freq of str2. Do the same for freq2.

3. Trim the string of white space. Split the string by whitespace and join by "%20".

OR: Use a regex to replace the whitespace with "%20"
The regex would be /(?<=\w)\s(?=\w)/g

4. Create a frequency counter to track the freq of each char. If the freq of each char except at most one, is 2, return true. Otherwise, return false. 

5. 