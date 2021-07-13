# Readability

| Name           | Description   |
|:-----------------------------|:--------------|
| automated_readability_index  |Automatic readability test that assesses the readability of a text|
|  |4.71 characters/words + 0.5 words/sentences - 21.43|
| coleman_liau_index           |Automatic readability test that assesses the readability of a text|
|  |0.0588L - 0.296S - 15.8, where L is the average number of letters per 100 words and S is the average number of sentences per 100 words|
| dale_chall_readability_score |Automatic readability test that assesses the readability of a text|
|  |15.79 difficultWords/words + 0.0496 words/sentences|
| flesch_kincaid_grade         |Automatic readability test that assesses the readability of a text|
|  |206.835 - 1.015 words/sentences - 84.6 syllables/words|
| flesch_reading_ease          |Automatic readability test that assesses the readability of a text|
|  |180 - words/sentences - 58.5 syllables/words|
| gunning_fog    |Automatic readability test that assesses the readability of a text|
|  |0.4 (words/sentences + 100 complexWords/words)|
| smog_index     |Automatic readability test that assesses the readability of a text|
|  |1.0430 root(polysyllables 30/sentences) + 3.1291|
|  |polysyllables are words with 3 syllables or more|

# Tense Features

| Name   | Description   |
|:---------------------|:--------------|
| clauses_per_sentence |The average number of clauses per sentence|
| fut_imperf           |Clauses with future imperfect in relation to all clauses|
| past_imperf          |Clauses with past imperfect in relation to all clauses|
| pres_imperf          |Clauses with present imperfect in relation to all clauses|
| pres_perf |Clauses with present perfect in relation to all clauses|

# Syntactical Features

| Name         | Description   |
|:---------------------------|:--------------|
| avg_chars_per_sentence     |Average number of characters per sentence of the website|
| avg_chars_per_word         |Average number of characters per word of the website|
| avg_sentence_length        |Average number of words per sentence of the website|
| avg_syllables_per_sentence |Average number of syllables per sentence of the website|
| avg_syllables_per_word     |Average number of syllables per word of the website|
| avg_words_per_sentence     |Average number of words per sentence of the website|
| count_characters           |Absolute number of characters per sentence of the website|
| count_sentences |Absolute number of sentences per sentence of the website|
| count_syllables |Absolute number of syllables per sentence of the website|
| count_words  |Absolute number of words per sentence of the website|
| reading_time |Display Reading Time for a website count_words/180|
| unique_word_ratio          |Ratio of unique words and all words of a website|

# Sentence Features

| Name   | Description   |
|:-------|:--------------|
| np     |Total number of nominal phrases|
| pp     |Total number of prepositional phrases|
| s      |Total number of single declarative clauses|
| vp     |Total number of verbal phrases|
| whnp   |Total number of wh-nominal phrases|

# Cohesive Complexity Feature

|Name| Description|
|:-----------------------------------------------------|:-----------------------------------------------------|
| Breindl Additive Connectives per Token       | Calculates the cohesive complexity of the text. This feature calculates the additive connectives listed by Breindl per token.  |
|           | 			Definition: # of additive connectives / # of token           |
| Breindl Adversative and Concessive Connectives per Token       | Calculates the cohesive complexity of the text. This feature calculates the adversative and concessive connectives listed by Breindl per token.  |
|           | 			Definition: # of adversative and concessive connectives / # of token           |
| Breindl All Connectives per Token | Calculates the cohesive complexity of the text. This feature calculates all the connectives listed by Breindl per Token.    |
|           | 			Definition: # of all connectives / # of tokens           |
| Breindl Causal Connectives per Token         | Calculates the cohesive complexity of the text. This feature calculates the causal connectives listed by Breindl per token. |
|           | 			Definition: # of temporal connectives / # of tokens           |
| Breindl Concessive Connectives per Token     | Calculates the cohesive complexity of the text. This feature calculates the concessive connectives listed by Breindl per token.           |
|           | 			Definition: # of concessive connectives / # of tokens           |
| Breindl Multi- to Single-Word Connectives    | Calculates the cohesive complexity of the text. This feature calculates the ratio of multi- to single-word connectives listed by Breindl. |
|           | 			Definition: # of multi-word connectives / # of single-word connectives           |
| Breindl Multi-Word Connectives per Connective    | Calculates the cohesive complexity of the text. This feature calculates the multi-word connectives per connective listed by Breindl.      |
|           | 			Definition: # of multi-word connectives / # of connectives           |
| Breindl Other Connectives per Token          | Calculates the cohesive complexity of the text. This feature calculates the other connectives listed by Breindl per token.  |
|           | 			Definition: # of other connectives / # of tokens           |
| Breindl Single-Word Connectives per Connective   | Calculates the cohesive complexity of the text. This feature calculates the single-word connectives per connective listed by Breindl.     |
|           | 			Definition: # of single-word connectives / # of connectives           |
| Breindl Single-Word Connectives per Token    | Calculates the cohesive complexity of the text. This feature calculates the single-word connectives listed by Breindl per token.          |
|           | 			Definition: # of single-word connectives / # of tokens           |
| Breindl Temporal Connectives per Token       | Calculates the cohesive complexity of the text. This feature calculates the temporal connectives listed by Breindl per token.  |
|           | 			Definition: # of temporal connectives / # of tokens           |

# Lexical Richness

|Name| Description|
|:-----------------------------------------------------|:-----------------------------------------------------|
| Type Token Ratio (Corrected TTR)          | Calculates the type token ratio of a text. A word type is   |
|           | 			a non-duplicated token.           |
|           | 			This features calculates the corrected TTR           |
|           | 			with the formula:           |
|           | 			CTTR = T/sqrt(2*N)           |
|           | 			T stands for number of word types,           |
|           | 			N for number of tokens.           |
| Type Token Ratio (Log TTR)  | Calculates the type token ratio of a text. A word type is   |
|           | 			a non-duplicated token.           |
|           | 			This features calculates the Bilogarithmic TTR           |
|           | 			with the formula:           |
|           | 			LogTTR = LogT/LogN           |
|           | 			T stands for number of word types,           |
|           | 			N for number of tokens.           |
| Type Token Ratio (Root TTR) | Calculates the type token ratio of a text. A word type is   |
|           | 			a non-duplicated token.           |
|           | 			This features calculates the root TTR with the           |
|           | 			formula:           |
|           | 			LogTTR = T/sqrt(N)           |
|           | 			T stands for number of word types, N for           |
|           | 			number of tokens.           |
| Type Token Ratio (TTR)  | Calculates the type token ratio of a text. A word type is   |
|           | 			a non-duplicated token.           |
|           | 			This features calculates the TTR with the           |
|           | 			formula:           |
|           | 			TTR = T/N           |
|           | 			T stands for number of word types, N for number of           |
|           | 			tokens.           |
| Type Token Ratio (Uber) | Calculates the type token ratio of a text. A word type is   |
|           | 			a non-duplicated token.           |
|           | 			This features calculates the Uber index with           |
|           | 			the formula:           |
|           | 			TTR = (LogN)^2/Log(N/T)           |
|           | 			T stands for number of word types,           |
|           | 			N for number of tokens.           |

# Lexical Sophistication

|Name| Description|
|:-----------------------------------------------------|:-----------------------------------------------------|
| Google Books 2000 Logarithmic Word Frequency (AW Token)     | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of all words (AW).           |
| Google Books 2000 Logarithmic Word Frequency (AW Type)      | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of all words (AW).           |
| Google Books 2000 Logarithmic Word Frequency (FW Token)     | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of functional words (FW).           |
| Google Books 2000 Logarithmic Word Frequency (FW Type)      | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of functional words (FW).           |
| Google Books 2000 Logarithmic Word Frequency (LW Token)     | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of lexical words (LW).           |
| Google Books 2000 Logarithmic Word Frequency (LW Type)      | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure) of lexical words (LW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (AW Token) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of all words (AW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (AW Type)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of all words (AW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (FW Token) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of functional words (FW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (FW Type)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of functional words (FW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (LW Token) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of lexical words (LW).           |
| Google Books 2000 Logarithmic Word Frequency Per Million Words (LW Type)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Log10 word frequency measure per million words) of lexical words (LW).           |
| Google Books 2000 Word Familiarity Per Million Words (AW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of all words (AW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| Google Books 2000 Word Familiarity Per Million Words (AW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of all words (AW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| Google Books 2000 Word Familiarity Per Million Words (FW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of functional words (FW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| Google Books 2000 Word Familiarity Per Million Words (FW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of functional words (FW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| Google Books 2000 Word Familiarity Per Million Words (LW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of lexical words (LW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| Google Books 2000 Word Familiarity Per Million Words (LW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Familiarity Per Million Words) of lexical words (LW). |
|           | 			Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.           |
| Google Books 2000 Word Frequency (AW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of all words (AW).           |
| Google Books 2000 Word Frequency (AW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of all words (AW).           |
| Google Books 2000 Word Frequency (FW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of functional words (FW).           |
| Google Books 2000 Word Frequency (FW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of functional words (FW).           |
| Google Books 2000 Word Frequency (LW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of lexical words (LW).           |
| Google Books 2000 Word Frequency (LW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list of lexical words (LW).           |
| Google Books 2000 Word Informativeness Per Million Words (AW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of all words (AW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| Google Books 2000 Word Informativeness Per Million Words (AW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of all words (AW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| Google Books 2000 Word Informativeness Per Million Words (FW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of functional words (FW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| Google Books 2000 Word Informativeness Per Million Words (FW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of functional words (FW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| Google Books 2000 Word Informativeness Per Million Words (LW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of lexical words (LW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| Google Books 2000 Word Informativeness Per Million Words (LW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Google Books 2000 word frequency list (Google Books 2000 Word Informativeness Per Million Words) of lexical words (LW). |
|           | 			Informativeness is the number of types with the same initial character trigram and of the same length as the given type.           |
| Mean Age of Active Use in KCT (AW Token)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of all words (AW).           |
| Mean Age of Active Use in KCT (AW Type)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of all words (AW).           |
| Mean Age of Active Use in KCT (FW Token)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of functional words (FW).           |
| Mean Age of Active Use in KCT (FW Type)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of functional words (FW).           |
| Mean Age of Active Use in KCT (LW Token)  | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of lexical words (LW).           |
| Mean Age of Active Use in KCT (LW Type)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Mean Age of Active Use in KCT list of lexical words (LW).           |
| Minimal Age of Active Use in KCT (AW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of all words (AW).           |
| Minimal Age of Active Use in KCT (AW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of all words (AW).           |
| Minimal Age of Active Use in KCT (FW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of functional words (FW).           |
| Minimal Age of Active Use in KCT (FW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of functional words (FW).           |
| Minimal Age of Active Use in KCT (LW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of lexical words (LW).           |
| Minimal Age of Active Use in KCT (LW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the Minimal Age of Active Use in KCT list of lexical words (LW).           |
| SUBTLEX Logarithmic Word Frequency (AW Token) | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of all words (AW).           |
| SUBTLEX Logarithmic Word Frequency (AW Type)  | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of all           |
|           | 			words (AW).           |
| SUBTLEX Logarithmic Word Frequency (FW Token) | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of           |
|           | 			functional words           |
|           | 			(FW).           |
| SUBTLEX Logarithmic Word Frequency (FW Type)  | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of           |
|           | 			functional words           |
|           | 			(FW).           |
| SUBTLEX Logarithmic Word Frequency (LW Token) | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of lexical           |
|           | 			words (LW).           |
| SUBTLEX Logarithmic Word Frequency (LW Type)  | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list (Log10 word frequency measure) of lexical           |
|           | 			words (LW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (AW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of all words (AW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (AW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of all words (AW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (FW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of functional words (FW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (FW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of functional words (FW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (LW Token)           | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of lexical words (LW).           |
| SUBTLEX Logarithmic Word Frequency Per Million Words (LW Type) | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (Log10 word frequency measure per million words) of lexical words (LW).           |
| SUBTLEX Word Familiarity Per Million Words (AW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of all words (AW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| SUBTLEX Word Familiarity Per Million Words (AW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of all words (AW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| SUBTLEX Word Familiarity Per Million Words (FW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of functional words (FW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| SUBTLEX Word Familiarity Per Million Words (FW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of functional words (FW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| SUBTLEX Word Familiarity Per Million Words (LW Token)       | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of lexical words (LW).           |
|           |  Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.          |
| SUBTLEX Word Familiarity Per Million Words (LW Type)        | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Familiarity Per Million Words) of lexical words (LW). |
|           | 			Familiarity is the cumulative frequency of all types with the same initial character trigram and of the same length as the given type.           |
| SUBTLEX Word Frequency (AW Token)         | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list of all words (AW).           |
| SUBTLEX Word Frequency (AW Type)          | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list of all words (AW).           |
| SUBTLEX Word Frequency (FW Token)         | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list of functional words (FW).           |
| SUBTLEX Word Frequency (FW Type)          | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW:           |
|           | 			all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and           |
|           | 			adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words           |
|           | 			that are included in the frequency list are calculated. Words           |
|           | 			that do           |
|           | 			not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into           |
|           | 			consideration all word tokens, while type           |
|           | 			features calculate only           |
|           | 			unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the           |
|           | 			SUBTLEX word           |
|           | 			frequency list of functional words (FW).           |
| SUBTLEX Word Frequency (LW Token)         | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list of lexical words (LW).           |
| SUBTLEX Word Frequency (LW Type)          | Calculates lexical sophistication of the text. Three        |
|           | 			sophistication measures are calculated from each frequency list:           |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words           |
|           | 			that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type           |
|           | 			features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word           |
|           | 			frequency list of lexical words (LW).           |
| SUBTLEX Word Informativeness Per Million Words (AW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of all words (AW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| SUBTLEX Word Informativeness Per Million Words (AW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of all words (AW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| SUBTLEX Word Informativeness Per Million Words (FW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of functional words (FW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| SUBTLEX Word Informativeness Per Million Words (FW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of functional words (FW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| SUBTLEX Word Informativeness Per Million Words (LW Token)   | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of lexical words (LW). |
|           |  Informativeness is the number of types with the same initial character trigram and of the same length as the given type.      |
| SUBTLEX Word Informativeness Per Million Words (LW Type)    | Calculates lexical sophistication of the text. Three sophistication measures are calculated from each frequency list:       |
|           | 			AW: all words           |
|           | 			LW: lexical words, which are verbs, nouns, adverbs and adjectives           |
|           | 			FW: function words, which are non-lexical words           |
|           | 			Only words that are included in the frequency list are calculated. Words that do not appear in the frequency list are omitted.           |
|           |           |
|           | 			Token features take into consideration all word tokens, while type features calculate only unique tokens.           |
|           |           |
|           | 			This feature calculates lexical sophistication with the SUBTLEX word frequency list (SUBTLEX Word Informativeness Per Million Words) of lexical words (LW). |
|           | 			Informativeness is the number of types with the same initial character trigram and of the same length as the given type.           |

# Lexical Variation

| Name           | Description   |
|:-----------------------------|:--------------|
| Adjective      | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Adjective variation with the following formula: |
|           |           |
|           | 	adjectiveVariation = nAdjectiveType / nLexicalToken           |
| Adverb         | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Adverb variation with the following formula:    |
|           |           |
|           | 	adverbVariation = nAdverbType / nLexicalToken           |
| Corrected Verb Variation 1       | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Verb variation with the following formula:      |
|           |           |
|           | 	CVV1 = nVerbType / sqrt(2 * nVerbToken)           |
| Lexical        | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates lexical variation with the following formula:   |
|           |           |
|           | 	lexicalVariation = nLexicalType / nLexicalToken           |
| Modifier       | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Modifier variation with the following formula:  |
|           |           |
|           | 	modifierVariation = nModifierType / nLexicalToken           |
|           |           |
|           | Modifiers are adjectives and adverbs.     |
| Noun           | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Noun variation with the following formula:      |
|           |           |
|           | 	nounVariation = nNounType / nLexicalToken           |
| Squared Verb Variation 1         | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Verb variation with the following formula:      |
|           |           |
|           | 	SVV1 = nVerbType^2 / nVerbToken           |
| Verb           | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Verb variation with the following formula:      |
|           |           |
|           | 	verbVariation = nVerbType / nLexicalToken           |
| Verb Variation 1   | Calculates lexical variation of the text. Lexical words are verbs, nouns, adjectives, and adverb. This feature calculates Verb variation with the following formula:      |
|           |           |
|           | 	VV1 = nVerbType / nVerbToken           |

# Syntactical Features

| Name           | Description   |
|:-----------------------------|:--------------|
| Mean Sentence Length in Letters           | Calculates the mean sentence length in letters.  |
| Mean Sentence Length in Syllables         | Calculates the mean sentence length in syllables.           |
| Mean Sentence Length in Tokens | Calculates the mean sentence length in number of letters.   |
| Mean Token Length in Letters   | Calculates the mean token length in letters.  |
| Mean Token Length in Syllables | Calculates the mean token length in syllables.   |
| Number Of Letters           | Count the number of letters in the document.  |

# Breindl Connectives

| Name           | Description   |
|:-----------------------------|:--------------|
| Breindl Additive Connectives         | Calculates the number of additive connectives according to Breindl.       |
| Breindl Adversative or Concessive Connectives      | Calculates the number of adversative or concessive connectives listed by Breindl.           |
| Breindl All Connectives   | Calculates the number of all connectives listed by Breindl. |
| Breindl Causal Connectives           | Calculates the number of causal connectives listed by Breindl. |
| Breindl Concessive Connectives       | Calculates the number of concessive connectives listed by Breindl.        |
| Breindl Multi-Word Connectives       | Calculates the number of all multi-word connectives listed by Breindl.    |
| Breindl Other Connectives | Calculates the number of unspecified connectives connectives listed by Breindl.  |
| Breindl Single-Word Connectives      | Calculates the number of all single-word connectives listed by Breindl.   |
| Breindl Temporal Connectives         | Calculates the number of temporal connectives listed by Breindl.          |
| Number of Sentences         | Calculates the number of sentences in a text. |
| Clauses | Calculates the number of a specific syntactic |
|           | 			constituents in the text. This feature counts the number of clauses           |
|           | 			in the text.           |

# Syntactic Constituents

| Name           | Description   |
|:-----------------------------|:--------------|
| Complex Noun Phrase       | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of complex noun phrases in the text.   |
| Complex Prepositional Phrase | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of complex prepositional phrases in the text.        |
| Complex T-units           | Calculates the number of a specific syntactic |
|           | 			constituents in the text. This feature counts the number of complex           |
|           | 			T-units in the text.           |
| Coordinate Phrases        | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of coordinate phrases in the text. |
| Dependent Clauses         | Calculates the number of a specific syntactic |
|           | 			constituents in the text. This feature counts the number of dependent           |
|           | 			clauses in the text.           |
| Noun Phrase | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of noun phrases in the text.       |
| Postnominal Noun Modifier | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of postnominal noun modifier in the text. |
| Prenominal Noun Modifier  | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of prenominal noun modifiers in the text. |
| Prepositional Phrase      | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of prepositional phrases in the text.  |
| Relative Clauses          | Calculates the number of a specific syntactic |
|           | 			constituents in the text. This feature counts the number of relative           |
|           | 			clauses           |
|           | 			in the text.           |
| Sentences   | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of sentences in the text.          |
| T-units | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of T-units in the text. |
| Verb Cluster   | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of verb clusters in the text.      |
| Verb Phrase | Calculates the number of a specific syntactic constituents in the text. This feature counts the number of verb phrases in the text.       |
| Number of Tokens | Calculates the number of tokens in the text.  |
| Number of Tokens with More Than 2 Syllables   | Calculates number of words tokens with more than 2          |
|           | 			syllables.           |
| Number of Word Types        | Calculates the number of word types. A word type is a       |
|           | 			non-duplicated token.           |
| Number of Word Types with More Than 2 Syllables  | Calculates number of words types with more than 2           |
|           | 			syllables.           |
| Number of syllables         | Calculates the number of syllables in the text.  |

# POS Density Feature

| Name           | Description   |
|:-----------------------------|:--------------|
| Adjective | Calculates adjective density of the text. |
|           | 			Adjectives           |
|           | 			include           |
|           | 			for English: the Penn Treebank tags JJ, JJR and JJS,           |
|           | 			for           |
|           | 			German: the Tiger tags ADJA and ADJD           |
|           |           |
|           | 			Formula:           |
|           | 			adjDensity =           |
|           | 			numAdjectives / numTokens           |
| Adverb | Calculates adverb density of the text.    |
|           | 			Adverbs include           |
|           | 			for           |
|           | 			English: the Penn Treebank tags RB, RBR, RBS, WRB.           |
|           | 			for German: the           |
|           | 			Tiger tag ADV.           |
|           |           |
|           | 			Formula:           |
|           | 			advDensity = numAdverbs / numTokens           |
| Article   | Calculates article density of the text.   |
|           | 			Articles           |
|           | 			for           |
|           | 			English: include the Penn Treebank tag DT,           |
|           | 			for German: the Tiger tag           |
|           | 			ART           |
|           |           |
|           | 			Formula:           |
|           | 			DTDensity = numDT / numTokens           |
| Auxiliary Verb       | Calculates Auxiliary Verb density of the text.   |
|           | 			Auxiliary Verbs include for German: the Tiger tags VAFIN VAIMP VAINF VAPP.           |
|           |           |
|           | 			Formula:           |
|           | 			auxVerbDensity = numAuxVerb / numTokens           |
| Cardinal Number      | Calculates cardinal number density of the text.  |
|           | 			Cardinal           |
|           | 			numbers include           |
|           | 			for English: the Penn Treebank tags CD,           |
|           | 			for German: the           |
|           | 			Tiger tag CARD           |
|           | 			Formula:           |
|           | 			CDDensity = numCDs / numTokens           |
| Common Noun          | Calculates Common Noun density of the text.   |
|           | 			Common Nouns include for German: the Tiger tag NN.           |
|           | 			This feature is not available for English.           |
|           |           |
|           | 			Formula:           |
|           | 			NNDensity = numNN / numTokens           |
| Comparative Conjunction  | Calculates the density of comparative conjunctions in the text.           |
|           | 			Comparative conjunctions include |
|           | 			for German: the Tiger tag KOKOM.           |
|           | 			This feature is not available for English.           |
|           |           |
|           | 			Formula:           |
|           | 			compConjDensity = numCompConj / numTokens           |
| Conjunction          | Calculates conjunction density of the text.   |
|           | 			Conjunctions           |
|           | 			include           |
|           | 			for English: the Penn Treebank tags CC, and IN,           |
|           | 			for German: the Tiger           |
|           | 			tags KOUI KOUS KON KOKOM.           |
|           |           |
|           | 			Formula:           |
|           | 			conjDensity = numConj / numTokens           |
| Coordinating Conjunction | Calculates conordinating conjunction density of the text.   |
|           | 			Coordinating conjunction include           |
|           | 			for English: the Penn Treebank tags           |
|           | 			CC,           |
|           | 			for German: the Tiger tag KON.           |
|           |           |
|           | 			Formula:           |
|           | 			CCDensity = numCC /           |
|           | 			numTokens           |
| Demonstrative Pronoun    | Calculates Demonstrative Pronoun density of the text.       |
|           | 			Demonstrative Pronouns include for German: the Tiger tags PDS PDAT.           |
|           | 			This feature is not available for: English.           |
|           |           |
|           | 			Formula:           |
|           |  demPronDensity = numDemPron / numTokens         |
| Determiner           | Calculates determiner density of the text.    |
|           | 			Determiners           |
|           | 			include           |
|           | 			for English: the Penn Treebank tags PDT, DT and WDT,           |
|           | 			for           |
|           | 			German: the           |
|           | 			Tiger tags ART PDAT PIAT PPOSAT PRELAT PWAT.           |
|           |           |
|           | 			Formula:           |
|           | 			detDensity = numDet / numTokens           |
| Finite Verb          | Calculates Finite Verb density of the text.   |
|           | 			Finite Verbs include for German: the Tiger tags VVFIN VVIMP VAFIN VAIMP VMFIN.           |
|           |           |
|           |           |
|           | 			Formula:           |
|           | 			finiteVerbDensity = numFiniteVerbs / numTokens           |
| Foreign Word         | Calculates foreign word density of the text.  |
|           | 			Foreign words           |
|           | 			include           |
|           | 			for English: the Penn Treebank tag FW,           |
|           | 			for German: the Tiger           |
|           | 			tag FM.           |
|           |           |
|           | 			Formula:           |
|           | 			FWDensity = numFWs / numTokens           |
| Functional Words     | Calculates functional word density of the text.  |
|           | 			Functional words include           |
|           | 			for English: the Penn Treebank tags CC, IN,           |
|           | 			PDT, DT, WDT,           |
|           | 			PRP, PRP$, WP,           |
|           | 			WP$, CD, EX, FW, LS, MD, POS, RP, SYM, TO,           |
|           | 			UH;           |
|           | 			for German: the Tiger           |
|           | 			tags CARD ITJ KOUI KOUS KON KOKOM PDS PDAT           |
|           | 			PIS PIAT PIDAT PPER PPOSS           |
|           | 			PPOSAT           |
|           | 			PRELS PRELSAT PRF PWS PWAT PWAV PAV           |
|           | 			PTKZU PTKNEG PTKVZ PTKANT PTKA VAFIN           |
|           | 			VAIMP VAINF VAIZU VAPP TRUNC           |
|           |           |
|           | 			Formula:           |
|           | 			functionalWordDensity = numFunctionalWords / numTokens           |
| Indefinite Pronoun   | Calculates Indefinite Pronoun density of the text.          |
|           | 			Indefinite Pronouns include for German: the Tiger tags PIAT PIDAT.           |
|           | 			This feature is not available for English.           |
|           |           |
|           | 			Formula:           |
|           | 			indefPronDensity = numIndefPron / numTokens           |
| Infinite Verb        | Calculates Infinite Verb density of the text. |
|           | 			Infinite Verbs include for German: the Tiger tags VVINF VAINF VMINF.           |
|           |           |
|           | 			Formula:           |
|           | 			infVerbDensity = numInfVerb / numTokens           |
| Interjection         | Calculates interjection density of the text. Interjections include        |
|           | 			for English: the Penn Treebank tags UH           |
|           | 			for German: the Tiger tag ITJ           |
|           |           |
|           | 			Formula:           |
|           | 			interDensity = numInter / numTokens           |
| Interrogative Pronoun    | Calculates Interrogative Pronoun density of the text.       |
|           | 			Interrogative Pronouns include for German: the Tiger tags PWS PWAT PWAV.           |
|           | 			This feature is not available for: English           |
|           |           |
|           | 			Formula:           |
|           | 			interPronDensity = numInterPron / numTokens           |
| Lexical Words        | Calculates lexical word density of the text. Lexical words include        |
|           | 			for English: the Penn Treebank tags JJ, JJR, JJS, RB, RBR, RBS, WRB, VB, VBD, VBG, VBN, VBP, VBZ;           |
|           | 			for German: the Tiger tags: ADJA ADJD ADV NN NE VVFIN VVIMP VVINF VVIZU VVPP VMFIN VMIMP VMINF VMIZU VMPP FM XY           |
|           |           |
|           | 			Formula:           |
|           | 			lexicalWordDensity = numLexicalWords / numTokens           |
| Main Verb | Calculates Main Verb density of the text. |
|           | 			Main Verbs include for German: the Tiger tags VVFIN VVIMP VVINF VVIZU VVPP.           |
|           |           |
|           | 			Formula:           |
|           | 			mainVerbDensity = numMainVerbs / numTokens           |
| Modal  | Calculates modal verb density of the text. Modal verbs include |
|           | 			for English: the Penn Treebank tags MD,           |
|           | 			for German: the Tiger           |
|           | 			tags VMFIN VMINF VMPP           |
|           |           |
|           | 			Formula:           |
|           | 			modalDensity = numModal / numTokens           |
| Modal Verb           | Calculates Modal Verb density of the text.    |
|           | 			Modal Verbs include for German: the Tiger tags VMFIN VMINF VMPP.           |
|           | 			Not available for: English |
|           |           |
|           | 			Formula:           |
|           | 			modalVerbDensity = numModalVerbs / numTokens           |
| Modifier  | Calculates density of modifier the text.  |
|           | 			Modifier are adverbs and adjectives and include           |
|           | 			for English: the Penn Treebank tags JJ, JJR, JJS, RB, RBR, RBS, WRB           |
|           | 			for German: the Tiger tag ADV, ADJA, ADJD.           |
|           |           |
|           | 			Formula:           |
|           | 			modDensity = numModifier / numTokens           |
| Non Finite Verb      | Calculates Non Finite Verb density of the text.  |
|           | 			Non Finite Verbs include for German: the Tiger tags VVINF VVIZU VVPP VAINF VAPP VMINF VMPP.           |
|           |           |
|           | 			Formula:           |
|           | 			nonFinVerbDensity = numNonFinVerb / numTokens           |
| Noun   | Calculates noun density of the text. Nouns include          |
|           | 			for English: the Penn Treebank tags NN, NNS, NNP and NNPS,           |
|           | 			for German: the Tiger tags NN NE.           |
|           |           |
|           | 			Formula:           |
|           | 			nounDensity = numNouns / numTokens           |
| Particle  | Calculates particle density of the text.  |
|           | 			Particles include           |
|           | 			for English: the Penn Treebank tag RP,           |
|           | 			for German: the Tiger tags PTKZU PTKNEG PTKVZ PTKANT PTKA           |
|           |           |
|           | 			Formula:           |
|           | 			RPDensity = numRPs / numTokens           |
| Past Participle Verb | Calculates past participle verb density of the text. Past particple verbs include           |
|           | 			for English: the Penn Treebank tag VBN,           |
|           | 			for German: the Tiger tags VVPP VMPP VAPP.           |
|           |           |
|           | 			Formula:           |
|           | 			VBNDensity = numVBNs /           |
|           | 			numTokens           |
| Personal Pronoun     | Calculates Personal Pronoun density of the text. |
|           | 			Personal Pronouns include for English: the Penn Treebank tag PRP,           |
|           | 			for German: the Tiger tags PPER PRF.           |
|           |           |
|           | 			Formula:           |
|           | 			persPronDensity = numPersPron / numTokens           |
| Possessive Pronoun   | Calculates possessive pronoun density of the text. Possesive pronouns include |
|           | 			for English: the Penn Treebank tag PRP$,           |
|           | 			for German: the Tiger tags PPOSS, PPOSAT           |
|           |           |
|           | 			Formula:           |
|           | 			PRPSDensity =           |
|           | 			numPRPSs           |
|           | 			/ numTokens           |
| Preposition          | Calculates preposition density of the text. Prepositions include          |
|           | 			for English: the Penn Treebank tags IN,           |
|           | 			for German: the Tiger tags APPR APPRART APPO APZR.           |
|           |           |
|           | 			Formula:           |
|           | 			PrepositionDensity =           |
|           | 			numPrepositions /           |
|           | 			numTokens           |
| Pronoun   | Calculates pronoun density of the text. Pronouns include    |
|           | 			for English: the Penn Treebank tags PRP, PRP$, WP, WP$,           |
|           | 			for German the Tiger tags: PDS PDAT PIS PIAT PIDAT PPER PPOSS PPOSAT PRELS PRELAT PRF PWS PWSAT PWAV PAV           |
|           |           |
|           | 			Formula:           |
|           | 			pronounDensity =           |
|           | 			numPronouns /           |
|           | 			numTokens           |
| Proper Noun          | Calculates Proper Noun density of the text.   |
|           | 			Proper Noun include for German: the Tiger tag NE.           |
|           | 			This feature is not available for English.           |
|           |           |
|           | 			Formula:           |
|           | 			NEDensity = numNE / numTokens           |
| Punctuation          | Calculates Punctuation density of the text.   |
|           | 			Punctuation includes for German: the Tiger tags $, $. $(           |
|           |           |
|           | 			Formula:           |
|           | 			punctDensity = numPunct / numTokens           |
| Relative Pronoun     | Calculates Relative Pronoun density of the text. |
|           | 			Relative Pronouns include for German: the Tiger tag PRELS PRELAT.           |
|           |           |
|           | 			Formula:           |
|           | 			relPronDensity = numRelPron / numTokens           |
| Singular Proper Noun | Calculates singular proper noun density of the text. Singular proper nouns include          |
|           | 			for English: the Penn Treebank tag NNP,           |
|           | 			for German: NE           |
|           |           |
|           | 			Formula:           |
|           | 			NNPDensity = numNNP / numTokens           |
| Subordinating Conjunction   | Calculates the density of Subordinating Conjunctions in the text.         |
|           | 			Subordinating Conjunction include           |
|           | 			for German: the Tiger tags KOUS KOUI.           |
|           | 			This feature is not available for English.           |
|           |           |
|           | 			Formula:           |
|           | 			subConjDensity = numSubordConj / numTokens           |
| To     | Calculates To density of the text. Tos include   |
|           | 			for English the Penn Treebank tag TO,           |
|           | 			for German the Tiger tags VVIZU |
|           |           |
|           | 			Formula:           |
|           | 			TODensity = numTOs / numTokens           |
| Verb   | Calculates verb density of the text.      |
|           | 			Verbs include for           |
|           | 			English: the Penn Treebank tags VB, VBD, VBG, VBN, VBP           |
|           | 			and           |
|           | 			VBZ,           |
|           | 			for           |
|           | 			German: the Tiger tags VVFIN VVIMP VVINF VVIZU VMFIN VMIMP VMINF           |
|           | 			VMIZU           |
|           | 			VMPP VAFIN VAIMP VAINF VAIZU VAPP           |
|           |           |
|           | 			Formula:           |
|           | 			verbDensity = numVerbs           |
|           | 			/ numTokens           |
| Percentage of Tokens with More Than 2 Syllables  | Calculates percentage of words tokens with more than 2      |
|           | 			syllables.           |
| Percentage of Word Types with More Than 2 Syllables         | Calculates the percentage of words types with more than 2   |
|           | 			syllables.           |
| SD Sentence Length in Letters  | Calculates the standard deviation of sentence length in number of letters.    |
| SD Sentence Length in Syllables           | Calculates the standard deviation of sentence length in number of syllables.  |
| SD Sentence Length in Tokens   | Calculates the standard deviation of sentence length in number of tokens. |
| SD Token Length in Letters  | Calculates the standard deviation of token length in        |
|           | 			number of letters.           |
| SD Token Length in Syllables   | Calculates the standard deviation of token length in        |
|           | 			number of syllables.           |

# Syntactic Complexity

| Name           | Description   |
|:-----------------------------|:--------------|
| Complex Nominals per Clause   | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex nominals per clause.           |
|           | 			Definition: # of complex nominals / # of clauses           |
| Complex Nominals per Sentence | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex nominals per sentence.           |
|           | 			Definition: # of complex nominals / # of sentences           |
| Complex Nominals per T-unit   | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex nominals per T-unit.           |
|           | 			Definition: # of complex nominals / # of T-units           |
| Complex Prepositional Phrases per Clause    | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex prepositional phrases per clause.           |
|           | 			Definition: # of complex prepositional phrases / # of clauses           |
| Complex Prepositional Phrases per Sentence  | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex prepositional phrases per sentence.           |
|           | 			Definition: # of complex prepositional phrases / # of sentences           |
| Complex Prepositional Phrases per T-Unit    | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the complex prepositional phrases per T-Unit.           |
|           | 			Definition: # of complex prepositional phrases / # of T-Units           |
| Complex T-unit Ratio          | Calculates the syntactic complexity of the text. This feature calculates the complex T-unit ratio.        |
|           | Definition: # of complex T-units / # of T-units  |
| Complex T-unit per Sentence   | Calculates the syntactic complexity of the text. This feature calculates the ratio of complex t-units to sentences.         |
|           | Definition: # of complex T-units / # of sentences           |
| Coordinate Phrases per Clause | Calculates the syntactic complexity of the text. This feature calculates the coordinate phrases per clause.   |
|           | Definition: # of coordinate phrases / # of clauses          |
| Coordinate Phrases per Sentence  | Calculates the syntactic complexity of the text. This feature calculates the coordinate phrases per sentence. |
|           | Definition: # of coordinate phrases / # of sentences        |
| Coordinate Phrases per T-unit | Calculates the syntactic complexity of the text. This feature calculates the coordinate phrases per T-unit.   |
|           | Definition: # of coordinate phrases / # of T-units          |
| Dependent clause ratio        | Calculates the syntactic complexity of the text. This feature calculates the dependent clause ratio.      |
|           | Definition: # of dependent clauses / # of clauses           |
| Dependent clauses per Sentence   | Calculates the syntactic complexity of the text. This feature calculates the dependent clause per sentence.   |
|           | Definition: # of dependent clauses / # of sentences         |
| Dependent clauses per T-unit  | Calculates the syntactic complexity of the text. This feature calculates the dependent clause per T-unit. |
|           | Definition: # of dependent clauses / # of T-units           |
| Mean Length of Clause         | Calculates the syntactic complexity of the text. This feature calculates the mean length of clause.       |
|           | Definition: # of word / # of clauses      |
| Mean Length of Complex T-unit | Calculates the syntactic complexity of the text. This feature calculates the mean length of complex T-unit.   |
|           | Definition: # of word / # of complex T-units  |
| Mean Length of Noun Phrase    | Calculates the syntactic complexity of the text. This feature calculates the mean length of noun phrase.  |
|           | Definition: # of word / # of noun phrases |
| Mean Length of Prepositional Phrase         | Calculates the syntactic complexity of the text. This feature calculates the mean length of prepositional phrase.           |
|           | Definition: # of word / # of prepositional phrases          |
| Mean Length of T-unit         | Calculates the syntactic complexity of the text. This feature calculates the mean length of T-unit.       |
|           | Definition: # of word / # of T-unit       |
| Mean Length of Verb Cluster   | Calculates the syntactic complexity of the text. This feature calculates the mean length of verb cluster. |
|           | Definition: # of word / # of verb cluster |
| Noun Phrases per Clause       | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the noun phrases per clause.           |
|           | 			Definition: # of noun phrases / # of clauses           |
| Noun Phrases per Sentence     | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the noun phrases per sentence.           |
|           | 			Definition: # of noun phrases / # of sentences           |
| Noun Phrases per T-unit       | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the noun phrases per T-unit.           |
|           | 			Definition: # of noun phrases / # of T-units           |
| Postnominal Modifier per Complex Noun Phrase    | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the postnominal modifier per complex noun phrase.           |
|           | 			Definition: # of postnominal modifier / # of complex noun phrases           |
| Prenominal Modifier per Complex Noun Phrase | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the prenominal modifier per complex noun phrase.           |
|           | 			Definition: # of prenominal modifier / # of complex noun phrases           |
| Prepositional Phrases per Clause | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the prepositional phrases per clause.           |
|           | 			Definition: # of prepositional phrases / # of clauses           |
| Prepositional Phrases per Sentence          | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the prepositional phrases per sentence.           |
|           | 			Definition: # of prepositional phrases / # of sentences           |
| Prepositional Phrases per T-Unit | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the prepositional phrases per T-Unit.           |
|           | 			Definition: # of prepositional phrases / # of T-Units           |
| Relative Clauses per Clause   | Calculates the syntactic complexity of the text. This feature calculates the relative clauses per clause. |
|           | Definition: # of relative clauses / # of clauses |
| Relative Clauses per Sentence | Calculates the syntactic complexity of the text. This feature calculates the relative clauses per sentence.   |
|           | Definition: # of relative clauses / # of sentences          |
| Relative Clauses per T-Unit   | Calculates the syntactic complexity of the text. This feature calculates the relative clauses per T-Unit. |
|           | Definition: # of relative clauses phrases / # of T-Units    |
| Sentence Complexity Ratio     | Calculates the syntactic complexity of the text. This       |
|           | 			feature calculates the sentence complexity ratio.           |
|           | 			Definition: # of clauses / # of sentences           |
| Sentence Coordination Ratio   | Calculates the syntactic complexity of the text. This feature calculates the sentence coordination ratio. |
|           | Definition: # of clauses / # of sentences |
| T-unit complexity ratio       | Calculates the syntactic complexity of the text. This feature calculates the T-unit complexity ratio.     |
|           | Definition: # of clauses / # of T-unit    |
| Verb Cluster per Clause       | Calculates the syntactic complexity of the text. This feature calculates the verb cluster per clause.     |
|           | Definition: # of verb cluster / # of clauses  |
| Verb Cluster per Sentence     | Calculates the syntactic complexity of the text. This feature calculates the verb cluster per sentence.   |
|           | Definition: # of verb cluster / # of sentences   |
| Verb Cluster per T-Unit       | Calculates the syntactic complexity of the text. This feature calculates the verb cluster per T-Unit.     |
|           | Definition: # of verb cluster / # of T-Units  |
| Verb Phrases per Clause       | Calculates the syntactic complexity of the text. This feature calculates the verb phrases per clause.     |
|           | Definition: # of verb phrases / # of clauses  |
| Verb Phrases per Sentence     | Calculates the syntactic complexity of the text. This feature calculates the verb phrases per sentence.   |
|           | Definition: # of verb phrases / # of sentences   |
| Verb Phrases per T-unit       | Calculates the syntactic complexity of the text. This feature calculates the verb phrases per T-unit.     |
|           | Definition: # of verb phrases / # of T-units  |
