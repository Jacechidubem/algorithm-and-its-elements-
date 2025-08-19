# Algorithm: English Sentence Analyzer
## Description
This  algorithm simply takes an inputed sentence and performs the operation listed below :
  - Counts the total number of characters,(excluding spaces).
  - counts the total number of words.
  - counts the total number of vowels in the sentence.
  ---

 Then it  uses a loop to scan through each character of the sentenece and checks:
  - If the character is a vowel ('a,e,i,o,u'). then it increments the vowel counter.
  - If the character is not a space , it increments the character counter.
  - If the character is a space , it increments the word counter.

  --- 
  ## pseudocode


```text
ALGORITHM english_sentence
VAR
    sentence: STRING[N]
    sentence_len: INTEGER
    word_count: INTEGER := 1
    vowel_count: INTEGER
    vowels: STRING:="aeiou"
BEGIN
    FOR i FROM 0 TO [N - 1] STEP 1  DO
        if (vowels.includes(sentence[i])) THEN
            vowel_count := vowel_count + 1
        END_IF
        IF (sentence[i] !== " ") THEN
            sentence_len := sentence_len + 1
        ELSE
            word_count := word_count + 1
        END_IF
    END_FOR
END
```
---
### Example run

#### Input:
 - I love programming.

#### Output
- vowel count :6
- character count :17
- Word count : 3
---
 #### String [N] is used because there isnt an inputed sentence yet. it simply means a sentence of lenght N
#### For i FROM 0 to N-1 simply means first character starts at 0 and last ends at N (number of sentences)-1 due to zero based indexing.
---
## Authors 
Joseph Enyinnia & Emmanuel Onyekwelu .
[github profile](https://github.com/Jacechidubem)
[repository link](https://github.com/Jacechidubem/algorithm-and-its-elements-.git)

