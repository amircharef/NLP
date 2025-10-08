👉🏻 Syntax concern the proper ordering of the word and its affect on meaning.
👉🏻 Concern with the structure of the sentence.
👉🏻 This involves analysis of the word in a sentence to depict the grammatical structure of the sentence.
👉🏻 it analyze the text for meaningfulness comparing to the rules of formal grammar.
👉🏻 The words are transformed into structure that shows how the words are related to each other. ➡️ **Dependency Parsing**
👉🏻 Eg. "the I present the course by NLP". this would definitely be rejected by the English synthetic analyzer
👉🏻 Parsing of the sentence - **noun**, **verbs**, **adjective** etc. ➡️ **Part-of-Speech Tagging**
👉🏻 Sometimes word order of some kind of structure causes misleading. like "I saw her with telescope"

![[Part-of-Speech Tagging.jpg | 600]]
![[Dependency Parsing.jpg | 600]]

| Tag  | Description                              |
| ---- | ---------------------------------------- |
| CC   | Coordinating conjunction                 |
| CD   | Cardinal number                          |
| DT   | Determiner                               |
| EX   | Existential there                        |
| FW   | Foreign word                             |
| IN   | Preposition or subordinating conjunction |
| JJ   | Adjective                                |
| JJR  | Adjective, comparative                   |
| JJS  | Adjective, superlative                   |
| LS   | List item marker                         |
| MD   | Modal                                    |
| NN   | Noun, singular or mass                   |
| NNS  | Noun, plural                             |
| NNP  | Proper noun, singular                    |
| NNPS | Proper noun, plural                      |
| PDT  | Predeterminer                            |
| POS  | Possessive ending                        |
| PRP  | Personal pronoun                         |
| PRP$ | Possessive pronoun                       |
| RB   | Adverb                                   |
| RBR  | Adverb, comparative                      |
| RBS  | Adverb, superlative                      |
| RP   | Particle                                 |
| SYM  | Symbol                                   |
| TO   | to                                       |
| UH   | Interjection                             |
| VB   | Verb, base form                          |
| VBD  | Verb, past tense                         |
| VBG  | Verb, gerund or present participle       |
| VBN  | Verb, past participle                    |
| VBP  | Verb, non-3rd person singular present    |
| VBZ  | Verb, 3rd person singular present        |
| WDT  | Wh-determiner                            |
| WP   | Wh-pronoun                               |
| WP$  | Possessive wh-pronoun                    |
| WRB  | Wh-adverb                                |

### Universal Dependency Relations
|        **Relation**         | **Description**           |                **Example**                 |
| :-------------------------: | :------------------------ | :----------------------------------------: |
|     **Core Arguments**      |                           |                                            |
|          **nsubj**          | Nominal Subject           |               **She** runs.                |
|          **csubj**          | Clausal Subject           |      **What she said** surprised me.       |
|           **obj**           | Object                    |           She wrote **a book**.            |
|          **iobj**           | Indirect Object           |          She gave **him** a book.          |
|          **ccomp**          | Clausal Complement        |      He said that **he was leaving**.      |
|          **xcomp**          | Open Clausal Complement   |          She wants **to leave**.           |
|   **Non-Core Dependents**   |                           |                                            |
|           **obl**           | Oblique Nominal           |        She walked **to the store**.        |
|          **advcl**          | Adverbial Clause Modifier |         He left **after he ate**.          |
|         **advmod**          | Adverbial Modifier        |            She ran **quickly**.            |
|          **expl**           | Expletive                 |           **There** is a house.            |
|       **dislocated**        | Dislocated Element        |     **The book**, I read it yesterday.     |
|        **vocative**         | Vocative                  |          **John**, can you help?           |
|   **Nominal Dependents**    |                           |                                            |
|          **nmod**           | Nominal Modifier          |         The door **of the house**.         |
|          **amod**           | Adjectival Modifier       |               a **red** car                |
|         **nummod**          | Numeric Modifier          |               **three** cars               |
|          **appos**          | Appositional Modifier     |            My friend, **John**             |
|           **det**           | Determiner                |                **The** car                 |
|          **case**           | Case Marker               |             a gift **for you**             |
|           **acl**           | Adjectival Clause         |        The man **who saw me** left.        |
| **Other Notable Relations** |                           |                                            |
|          **acomp**          | Adjectival Complement     |             She is **happy**.              |
|           **aux**           | Auxiliary                 |         She **has been** running.          |
|           **cop**           | Copula                    |            She **is** a doctor.            |
|          **mark**           | Marker                    |         **If** you go, I will go.          |
|          **conj**           | Conjunct                  |           apples **and** oranges           |
|           **cc**            | Coordinating Conjunction  |           apples **and** oranges           |
|          **punct**          | Punctuation               |               She left **.**               |
|          **root**           | Root                      |          **run** (in “She runs.”)          |
|           **dep**           | Unspecified Dependency    | Used for **unclassifiable relationships**. |