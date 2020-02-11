# Ransom Note

Given an arbitrary ransom note string and another string containing letters from all the magazines, write a funciton that will return true if the ransom note can be constructed from the magazines; otherwise, it will return false.

Each letter in the magazine string can only used once in your ransom note.

**Note:**  
You may assume that both strings contatin only lowercase letters.  

canConstruct("a", "b") -> false  
canConstruct("aa", "bb") -> false  
canConstruct("aa", "aab") -> true