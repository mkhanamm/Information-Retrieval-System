An Information Retrieval (IR) system for Indian languages, designed to process and search text written in multiple Indian scripts such as Devanagari (Hindi.)
It demonstrates how traditional IR techniques work in a multilingual and non-English setting, where text processing is more challenging due to different scripts, tokenization rules, and language-specific variations
Think of the project as building a mini Google Search Engine for HINDI 
Main Features
1. Text Preprocessing & Corpus Analysis
Tokenization of words in an Indian script
Unicode normalization for consistent text representation
Stopword removal
Optional stemming/lemmatization
Corpus statistics analysis using:
Zipf's Law
Heaps' Law
Generation of vocabulary statistics and log-log plots
Building the Search Engine 
2. Inverted Index Construction & Compression
Build an inverted index from scratch
Store:
Dictionary of terms
Term Frequencies (TF)
Document Frequencies (DF)
Support:
Boolean Queries (AND, OR, NOT)
Phrase Queries
Implement positional indexing
Serialize and deserialize indexes
Index compression using:
Gap Encoding
Making Search Smarter 
3. Tolerant Retrieval
Wildcard Search
K-gram indexing
Leading, trailing, and middle wildcards
Candidate filtering and verification
Transliteration Search
Search using Latin script and retrieve results in native script
Support multiple transliteration mappings
Example: "bharat" → "భారత్" / "भारत"
Bonus Features
Sandhi/compound word handling
Phonetic/confusable character matching
Cross-script search (e.g., Hindi query on Telugu documents)

Variable Byte Encoding or Gamma Encoding
Measure compression ratio and storage savings
