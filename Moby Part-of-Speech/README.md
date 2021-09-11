The **Moby Part-of-Speech II** is a list of words described by their part(s) of speech. According to it's documentation, it's unquestionably the largest part-of-speech list in the world when it was written.  This is the second version of the original **Moby Part-of-Speech**. There has been more than 15,000 new entries and thousands of entries have been updated.

## Legend
Each part-of-speech vocabulary entry consists of a word or phrase field followed by a field delimiter of the backslash (\) and their part(s) of speech field that is coded using the following ASCII symbols (case is significant):
|Part-of-speech| Code |
|--|--|
| Noun | N |
| Plural | p|
| Noun phrase | h |
| Verb (usually participle) | V |
| Transitive verb | t |
| Intransitive verb | i |
| Adjective | A |
| Adverb | v |
| Conjunction | C |
| Preposition | P |
| Interjection | ! |
| Pronoun | r |
| Definite article | D |
| Indefinite article | I |
| Nominative | o |

This two-part vocabulary record is delimited from others with CRLF (ASCII 13/10).  For example, `engineer\Nt` means that the word engineer has two main uses in English; the principal part-of-speech is as a noun "That engineer could write in microcode with one hand and in ADA with the other" and its secondary part-of-speech is as a transitive verb: "We sure engineered that software to death."

In many cases, the `-ed`, `-ing`, `-ly`, and `-ic` forms of words are not explicitly listed; the participle forms of verbs will be usually marked simply with the V sign rather than the more specific t or i symbols.  Words such as `be`, which often have more than one head entry in a dictionary, have one listing with all the parts-of-speech for all senses concatenated.  Foreign words commonly used in English usually include their diacritical marks, for example, the acute accent e is denoted by ASCII 142.
