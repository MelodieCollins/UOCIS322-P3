# UOCIS322 - Project 3 #

A simple anagram game designed for English-language learning students in elementary and middle school. Students are presented with a list of vocabulary words (taken from a text file) and an anagram. The anagram is a jumble of some number of vocabulary words, randomly chosen. Students attempt to type words that can be created from the jumble. When a matching word is typed, it is added to a list of solved words.

The vocabulary word list is fixed for one invocation of the server, so multiple students connected to the same server will see the same vocabulary list but may have different anagrams.

I copied flask_vocab.py into flask_edited.py where I did all of my editing. Hence Dockerfile uses flask_edited.py which is also linked to vocab_edited.html.

## Author

Melodie Collins, mcolli11@uoregon.edu

## Date

May 2, 2021


## Credits

Michal Young, Ram Durairajan, Steven Walton, Joe Istas.
