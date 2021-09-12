The **Moby Pronunciator II** has lists containing words with their corresponding pronunciation.

## 177,267 entries in [`mpron.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Pronunciator%20II/mpron.txt)
This is the main **Moby Pronunciator II** dictionary.  According to it's documentation in [`phoneset.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Pronunciator%20II/phoneset.txt), each entry consists of a word or phrase field followed by a field delimiter of space " " and the IPA equivalent field that is coded using the following ASCII symbols (case is significant). Spaces between words in the  word or phrase or pronunciation field is denoted with underscore. The lines are in the fomat: *word[/part-of-speech] pronunciation*.

The *part-of-speech* field is optional and only used to disambiguate 770 of the words which have differing pronunciations depending on their part-of-speech. According to Wikipedia and it's documentation, the parts-of-speech have been assigned the following codes:
| Part of Speech | Code |
|--|--|
| Noun | n |
| Verb | v |
| Adjective | aj |
| Adverb | av |
| Interjection | interj |
 
 Various symbols used in this list are:
| Symbol | Meaning |
|--|--|
| _ | To seperate words |
| ' | Primary stress on the following syllable |
| , | Secondary stress on the following syllable |

The rest of the characters are IPA symbols denoting the pronunciation. Each phoneme is represented by a sequence of one or more characters. Some of the sequences are delimited with a slash character "/", as shown in the following table, but note that the sequence for /ɔɪ/ is delimited by _two_ slash characters at either end. The IPA symbols used are:
| Symbol | IPA    | Sounds like                                        |
|--------|--------|----------------------------------------------------|
| /&/    | æ      | "a" in "dab"                                       |
| /-/    | ə      | "ir" glide in "tire" or the "dl" glide in "handle" |
| /@/    | ʌ, ə   | "a" in "ado"                                       |
| /[@]/r | ɜr, ər |                                                    |
| /A/    | ɑ, ɑː  | "a" in "far"                                       |
| /aI/   | aɪ     | "i" in "ice"                                       |
| /AU/   | aʊ     | "ow" in "how"                                      |
| b      | b      | "b" in "nab"                                       |
| d      | d      | "d" in "pod"                                       |
| /D/    | ð      | "th" in "the"                                      |
| /dZ/   | dʒ     | "g" in "vegetably"                                 |
| /E/    | ɛ      | "e" in "red"                                       |
| /eI/   | eɪ     | "a" in "day"                                       |
| f      | f      | "f" in "elf"                                       |
| g      | ɡ      | "g" in "fig"                                       |
| h      | h      | "h" in "had"                                       |
| hw     | hw     | "w" in "white"                                     |
| /i/    | iː     | "e" in "see"                                       |
| /I/    | ɪ      | "i" in "hid"                                       |
| /j/    | j      | "y" in "you"                                       |
| /ju/   | juː    |                                                    |
| k      | k      | "c" in "act"                                       |
| l      | l      | "l" in "ail"                                       |
| m      | m      | "m" in "aim"                                       |
| n      | n      | "n" in "and"                                       |
| /N/    | ŋ      | "ng" in "bang"                                     |
| /O/    | ɔ, ɔː  | "o" in "dog"                                       |
| //Oi// | ɔɪ     | "oi" in "oil"                                      |
| /oU/   | oʊ     | "o" in "boat"                                      |
| p      | p      | "p" in "imp"                                       |
| r      | r      | "r" in "ire"                                       |
| s      | s      | s" in "sip"                                        |
| /S/    | ʃ      | sh" in "she"                                       |
| t      | t      | "t" in "tap"                                       |
| /T/    | θ      | "th" in "bath"                                     |
| /tS/   | tʃ     | "ch" in "ouch"                                     |
| /u/    | uː     | "oo" in "too"                                      |
| /U/    | ʊ      | "oo" in "book"                                     |
| v      | v      | "v" in "average"                                   |
| w      | w      | "w" in "win"                                       |
| z      | z      | "z" in "zoo"                                       |
| /Z/    | ʒ      | "s" in "vision"                                    |

There are several other extra sequences representing phonemes found in other languages. Some of these might be errors in encoding because the documentation hasn't addressed all the extra phonemes.

| Symbol |               IPA               | Addressed in documentation |
|:------:|:-------------------------------:|:--------------------------:|
| A      | a                               |             Yes            |
| e      | e, ɛ                            |                            |
| i      | i, ɪ                            |                            |
| N      | Nasalisation of preceding vowel |             Yes            |
| o      | o                               |                            |
| O      | [intent not clear]              |                            |
| R      | ʁ                               |             Yes            |
| S      | s                               |                            |
| u      | u                               |                            |
| V      | v, β, ʋ                         |                            |
| W      | w                               |                            |
| /x/    | x                               |             Yes            |
| /y/    | ø                               |             Yes            |
| Y      | y                               |             Yes            |
| /z/    | ts                              |                            |
| Z      | z                               |                            |

To this collection are added a number of extra sequences representing phonemes found in several other languages. These are used to encode the non-English words, phrases and names that are included in the database. The following table contains these extra phonemes, but note that the extent to which some of these may exist due to encoding errors is not clear.

The documentation states that words and phrases adopted from languages other than English have the unaccented form of the roman spelling. For example, *etude* has an initial accented *e* but is spelled without the accent in the Moby Pronunciator II database. According to Wikipedia, in 36 entries (e.g.  _São_Miguel_), some non-ASCII accented characters remain, represented using Mac OS Roman encoding.

## 110,935 entries in Carnegie Mellon Pronouncing Dictionary ([`cmudict.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Pronunciator%20II/cmudict.txt))
The **CMU Pronouncing Dictionary** is an open-source pronouncing dictionary originally created by the Speech Group at  [Carnegie Mellon University](https://en.wikipedia.org/wiki/Carnegie_Mellon_University "Carnegie Mellon University") (CMU) for use in speech recognition research. The version of [`cmudict.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Pronunciator%20II/cmudict.txt) in this directory is `0.3.Z`, although the most recent release is `0.7b`.

The database is distributed as a plain text file with one entry to a line in the format `WORD  <pronunciation>` with a two-space separator between the parts. If multiple pronunciations are available for a word, variants are identified using numbered versions (e.g. `WORD(1)`). For more info, see [`abreadme.txt`](https://github.com/elitejake/Moby-Project/blob/main/Moby%20Pronunciator%20II/abreadme.txt) and [it's Wikipedia article](https://en.wikipedia.org/wiki/CMU_Pronouncing_Dictionary).
