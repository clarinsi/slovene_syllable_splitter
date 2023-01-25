# slovene_syllable_splitter
A rule-based syllable splitter for Slovene that takes an input word and returns a list of syllables in the word, e.g. predsedovati -> ['pred', 'se', 'do', 'va', 'ti']; decembrskega -> ['de', 'cem', 'brs', 'ke', 'ga'].


A word is split into syllables by calling the 'create_syllables' function as shown below:
```
syllables = create_syllables(word="decembrskega", vowels=get_vowel_graphemes())
print(syllables)
```
