public class Solution {
    public boolean isAnagram(String s, String t) {
        char[] Sarr=s.toCharArray();
        char[] Tarr=t.toCharArray();
        Array.sort(Sarr);
        Array.sort(Tarr);
        return String.valueOf(Sarr).equals.(String.valueOf(Tarr));
    }
}
