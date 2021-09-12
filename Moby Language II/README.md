**Moby Language II** has wordlists of 5 languages: French, German. Italian, Japanese and Spanish.

## Historical Note
**Source:** [Project Gutenberg](https://www.gutenberg.org/files/3206/3206.txt)

The Ward word lists were some of the largest public domain word lists in the world, at the time they were added to the Project Gutenberg collection in 2007. These word lists do not contain 8-bit accented characters or Unicode, as would be found in a more recent Project Gutenberg eBook. Instead, the lists include phonetic spelling, utilizing backslashes and other characters to indicate where accents would normally occur. There is no detailed guide on how these extra characters were used, and therefore it is likely infeasible to map from the word lists back to a correct representation of the word (i.e., to map from a word list entry with slashes or other characters, back to the actual non-English word with accents or other non-ASCII characters).

These lists may still be useful, but they are no longer the state-of-the-art in wordlists. In the time since the lists were created, it has become much easier for anyone with interests to make their own lists of unique words from the Project Gutenberg collection or other sources.

## Issues
According to Wikipedia, some of the lists are contaminated. For example,  [`japanese.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Language%20II/japanese.txt) has English words such as *abnormal* and words that do not exist, like *abcdefgh* and *m,./*. The words aren't sorted consistently among the lists. [`french.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Language%20II/french.txt) contains a straight alphabetical listing, while the [`german.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Language%20II/german.txt) contains the alphabetical listing of traditionally capitalized words and then the alphabetical listing of traditionally lower-cased words. However, [`italian.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Language%20II/italian.txt) does not contain any capitalized words. None of these lists use accented characters, so "e^tre" is how a user would look up the French word  *être* (*to be*).

## Statistics
| Language | Words | Size (in bytes)
|--|--|--|
| **French** | 138,257 | 1,524,757 |
| **German** | 159,809 | 2,055,986 |
| **Italian** | 60,453 | 561,981 |
| **Japanese** | 115,523 | 934,783 |
| **Spanish** | 86,059 | 850,523 |
| **Total** | **560,101** | **5,928,030**
