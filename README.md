**Description**

This program centers on the creation of a word ladder that connects two English words using a dictionary of the full English language from a dynamic heap-allocated array of C strings and triple pointers. You can utilized UNIX command-line arguments for several tasks: setting the word length for the starting and final words for the word ladder; setting the maximum allowed word ladder height, which sets the maximum capacity for the dynamic array of C-strings that will represent the word ladder; interactively setting the dictionary file name, **dict,** to be used for reading words into the full array of possible woords that could later make up the ladder.


**Summary**

A word ladder is a bridge between one word and another, formed by changing one letter at a time, with the constraint that at each step the sequence of letters still forms a valid word. This project allows the user to generate valid word ladders using a real English dictionary. The dictionary file is opened and each dictionary is scanned. Words that have the correct length are added to the dynamic **words** array, which starts at a maximum capacity of **4 C-string pointers** and double in capacity whenever more space is needed. 

**Dictionary Files**

The provided file _dictionary.txt_ contains the full contents of the "Official Scrabble Player's Dictionary, Second Edition." This word list has over 120,000 words, which is more than enough for the purposes of making word ladders for small to moderate sized words. Smaller dictionaries are also provided for testing purposes: _simple3.txt_ contains a limited number of 3-letter words, _simple4.txt_ contains a limited number of 4-letter words, and _simple5.txt_ contains a limited number of 5-letter words. Also, _sampleDict.txt_ contains a small number of words, with varying word lengths, but you can still make an interesting word ladder connecting toe -> ear. 
