👉🏻 it Known also as **Morphological Analysis**.
👉🏻Morphemes are the smallest indivisible meaningful units of a language which builds a word
👉🏻 The lexicon of the language is its vocabulary that includes its words and expression.
👉🏻 Morphology depicts analyzing, identifying and description of structure of word. 

> [!example]
>**Plural**: cat-s, fox-es, fish
**Tense**: walk-s, walk-ed
**Nominalization:** kill-er, fuzz-iness
**Compounding**: book-case,over-load,wash-cloth

👉🏻 Two Type of Morphemes
```
			 Morphemes
			/          \
		Stem           affixes
	(Root Word)        prefixes - infix - suffix
```




👉🏻 Lexical analysis involves diving a text into paragraphs, words and sentences. ➡️ **Tokenization**
👉🏻 **Lexical Normalization**: Involves processes like stemming (reducing words to their root form) or lemmatization (converting words to their base or dictionary form), and handling slang or abbreviations, for example, Unfortunately can be broken to Un (prefix), fortunate (root) an ly (suffix) ➡️ **Stemming**
👉🏻 Finding the dictionary form of a word ➡️ **Lemmatization**

![[Stemming-vs-Lemmatization.jpg | 500]]
![[Stemming vs Lemmatization02.png | 500]]

## MORPHOLOGICAL PARSER

--- start-multi-column: ID_bmvm
```column-settings
Number of Columns: 3
Largest Column: standard
```

####  Lexicon
- Stores basic information about a word.
- Determines if a word is a stem or an affix.
- If it's a stem, it identifies if it is a Verb Stem or Noun Stem.
- If it's an affix, it identifies if it is a prefix, infix, or suffix.


--- column-break ---
#### Morphotactic

- A set of rules to make decisions.
- Decides the correct order of morphemes (the parts of a word).
- For example:
    - **Valid:** re + act + ion → reaction (This follows the rule: prefix + stem + suffix)
    - **Invalid:** act + ion + re → actionre (This violates the rule for placing the prefix re-)

--- column-break ---
#### Orthographic rules

- A set of rules used to decide spelling changes when combining morphemes.
- For example:
    
    - puppy + s → puppies (The 'y' changes to 'ies')
    - stop + ed → stopped (The final consonant is doubled)
    - wolf + s → wolves (The 'f' changes to 'ves')

--- end-multi-column
## MORPHOLOGICAL ANALYSIS
- Some words have their own meaning. For example: House, Water, Tree

- Some words, when divided into different parts, result in new words that also have their own meaning. For example:
    - **Rainbow** → Rain + bow
    - **Football** → Foot + ball

- Some parts of words do not have their own meaning, but they become meaningful when they are combined with other words. For example, the prefix **un-**:    
    - Can be added to make words like **unhappy** and **unable**.
        

Thus, the detailed study of the making of words is called **Morphological Analysis**.
