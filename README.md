The tokenizer accepts Urdu text as input.

=======================================================================
- use of start-of-sentence & end-of-sentence words
- Tokenization Logic:
-- The main function uses regular expressions or other linguistic rules specific to Urdu to identify sentence boundaries.
-- This involves looking for punctuation marks typical for ending sentences, such as periods, question marks, or exclamation points, and considering Urdu-specific cases like ending postpositions.

- Output Generation:
-- Once the text is segmented into sentences, the tokenizer returns these as a list or another structured format suitable for downstream processing.
  
=======================================================================
This tokenizer be used in applications like sentiment analysis, translation, or other text analysis tasks that require sentence-level processing.
