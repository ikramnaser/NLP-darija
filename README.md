## What the project does
Welcome to the NLP-Darija project in which I delve into exploring existing natural language processing techniques tailored for Moroccan Darija, a low-resource language with its unique linguistic challenges in order to perform Moroccan Darija to English Machine Translation. 
I compare and evaluate the performance of LLMs (GPT-4 and Claude) for sentence level translation, idiomatic expressions and for POS tagging and dependency parsing implementation on code-switched text. 

### Why the project is useful
This repository serves as a statement to highlight the significant gaps that remain in the NLP community's efforts to support low-resource languages, particularly those that exist in both standardized and non-standardized scripts like Arabizi. 





## Data Statement

Darija Open Dataset (DODa) is an open-source project for the Moroccan dialect, is arguably the largest open-source collaborative project for Darija-English translation.
DODa contains more than 10 thousand entries covering verbs, nouns, adjectives, verb-to-noun, singular to-plural correspondences, conjugations of hundreds of verbs in different tenses. The Dataset is also divided into specialized subcategories such as food, animals, human body, health, education, family, environment, economy and many others. Besides semantic categorization, it presents words under different spellings, offers verb-to-noun and masculine-to-feminine correspondences, extra categories for idioms, proverbs and short expressions, as well as more that 86,000 translated sentences.


### curation rationale
My curation prioritized linguistic phenomena relevant to my project goals namely investigating spelling variations, and syntactic challenges in code-switching. Specifically, the dataset includes 65 idioms and proverbs, 241 words under different spellings and almost 46k translated sentences.
To investigate code-switching phenomena, I constructed a custom corpus using online sources. To extract song lyrics, I scraped the website genius.com through the Genius API, used multiple queries to extract song lyrics by Moroccan artists who are known to include many instances of Code Switching in their words. Moroccan Darija was the main (matrix) language while other languages such as French and English were present as guest (embedded) languages.


### language variety
The language of my dataset is Moroccan Darija written in Latin script, ary-Latn-MA. For the sake of simplicity and consistency, the dataset focuses on the standard Darija spoken and understood by the majority of Moroccans. And to align with the real-world usage and informal communication, only the Darija written in Latin script will be taken into account.


### speaker demographics
NA

### annotator demographics
NA

### speech situation
NA

### text characteristics
The Arabic script column from the original dataset was excluded to focus solely on the Latin-script representation of Darija. Additionally, idioms and proverbs were consolidated into a single dataset.
To maintain phonetic clarity and consistency, the dataset adheres to the correspondences and norms detailed in the following tables:

### recording quality
NA

### provenance
NA
