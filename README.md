# wikipedia-data

``/word-frequency/`` contains analysis on word frequency from a full wikipedia dump in different languages, we used [cvstools](https://github.com/dabinat/cvtools/) to generate it.

- ``word-frecuency.es.txt`` - Spanish wikipedia (2955930 words)

``/complex-words/`` contains analysis on less common words used in different wikipedias, this can be used as blacklist to clean up words that are complex, non-native or with weird characters combination. Each language has a different word frequency limit.

- ``complex.es.txt`` - Spanish wikipedia, words with 80 or less repetitions (2827258 words)
