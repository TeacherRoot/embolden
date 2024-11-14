# embolden
Embolden Project in Java
Implement the method public static void embolden(String s, String[] lst) 
which takes in a string s and an array of substrings lst, and wraps all substrings in s with an HTML bold tag <b> and </b>.

 If two bold tags overlap or are contiguous, they should be merged.
 
 For example, given s = abcdefg and lst = ["bc", "ef"], return the string abcdefg.

 

Given s = abcdefg and lst = ["bcd", "def"], return the string abcdefg, since they overlap.
