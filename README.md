# Leetcode---1910
Remove All Occurrences of a Substring
//code in java
class Solution {
    public String removeOccurrences(String s, String part) {
        while (s.contains(part)) {
            s = s.replaceFirst(part, ""); // Remove first occurrence of 'part'
        }
        return s;
    }
}
