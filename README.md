# Instructions to Add a New Language

Supporting a new language is a process that demands complex language data mostly collected from researchers in local Universities. Having this data a neural network is trained with them and the language is available to use in NLP algorithms. The necessary data are:

- **Treebanks** (https://en.wikipedia.org/wiki/Treebank): In linguistics, a treebank is a parsed text corpus that annotates syntactic or semantic sentence structure. There are many of them available on the internet for the most spoken languages, we are getting this piece of information from this website: http://universaldependencies.org/​

- **Lemmas** (https://en.wikipedia.org/wiki/Lemma_(morphology)): In morphology and lexicography, a lemma (plural lemmas or lemmata) is the canonical form, dictionary form, or citation form of a set of words (headword)[citation needed]. In English, for example, run, runs, ran and running are forms of the same lexeme, with run as the lemma;

  Expected Format:

  | Inflected form | Lemma |
  | -------------- | ----- |
  | men            | man   |
  | worked         | work  |
  | goes           | go    |
  | going          | go    |

  ​

- **Contracted Words** (https://en.wikipedia.org/wiki/Contraction_(grammar)): A contraction is a shortened version of the written and spoken forms of a word, syllable, or word group, created by omission of internal letters and sounds.

  Expected Format:

  | Contraction | First part | Second part |
  | ----------- | ---------- | ----------- |
  | we'll       | we         | will        |
  | i'm         | i          | am          |



- **Personal Pronouns** (https://en.wikipedia.org/wiki/Personal_pronoun): Personal pronouns are [pronouns](https://en.wikipedia.org/wiki/Pronoun) that are associated primarily with a particular [grammatical person](https://en.wikipedia.org/wiki/Grammatical_person) – first person (as *I*), second person (as *you*), or third person (as *he*, *she*, *it*, *they*).

  Expected Format:

  | Pronoun |
  | ------- |
  | i       |
  | me      |
  | you     |
  | he      |
  | she     |
  | it      |
  | ...     |

  ​

- **Same Spelling**: Words that can be spelled in the same way.

  Expected Format:

  | First word | Second word |
  | ---------- | ----------- |
  | color      | colour      |
  | cos        | because     |

  ​

- **Stop Words** (https://en.wikipedia.org/wiki/Stop_words): Common words that carry little semantic meaning.

  Expected Format:

  | Stop word |
  | --------- |
  | a         |
  | about     |
  | after     |
  | so        |
  | that      |

  ​



