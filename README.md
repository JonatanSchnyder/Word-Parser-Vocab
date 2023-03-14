# Word-Parser-Vocab
This repository parses simple vocabulary into a format that is accepted by Quizlet and Anki

# Input Format
- The Input Format of the file is in lines. The translations are listed separated by lines and else
- For Example the english word `the house` translated to french is `la maison`. Used is it as 
```
the house - la maison
to visite - visiter
```
# Output Format
The Output Format is dependent on the recipient it will go to.

## Quizlet
The Quizlet requires a format with
```
Word1;Word2
Word3;Word4
```
## Anki
Anki requires Quotation Marks `"` surrounding the words and a semicolon `;` inbetween. One line for a word. No tabs allowed.
```
"Word1";"Word2"
"Word3";"Word4"
```
