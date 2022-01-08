# String-repeat
 // Write a function called repeatStr which 
    // repeats the given string
    //  string exactly n times.
    Solution:
    function repeatStr(count, str) {
    let repeatedString = "";
    for (i = 0; i < count; i++) {
        repeatedString += str;
    }
    return repeatedString;
}
