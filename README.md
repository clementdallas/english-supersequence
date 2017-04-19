A search for a shortest common supersequence of the set of english words. 

For this project, the set of english words is defined as those found in words.txt. The current shortest common supersequence
is found in shortest.txt.

# Contributing
Replace shortest.txt with a shorter common supersequence (the sequence should be the only thing in the file)
and open a pull request. 

# Background information

An english word, such as 'cellar', is a sequence of letters from the english alphabet. A sequence is distinct from a set
in that the order of the letters matters, for example 'cellar' is not the same as 'erllac'.

The sequence 'cellar' is a supersequence of 'car' because each letter in 'car' occurs, in order, in the word 'cellar'.  
The word 'create' is not a super sequence of 'car', even though it contains the letters c, a and r, because the letters are not in the right order.

The word 'cellar' is a common supersequence to the words 'cell' and 'car' because it is a supersequence of both words.

The shortest common supersequence problem is to find the minimal length of a supersequence of a given set of words. https://en.wikipedia.org/wiki/Shortest_common_supersequence_problem

The shortest common supersequence of english depends on the words considered, and for this project all english words are those found in words.txt. This file was created using the wordlists american-english and british-english in /usr/share/dict. All words with uppercase or special characters were removed, so that the alphabet is a-z. 

Determining the length of the shortest common supersequence is an NP-complete problem, so this search should have no end. 



