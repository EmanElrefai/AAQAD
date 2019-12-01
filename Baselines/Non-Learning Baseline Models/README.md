We  evaluate  non-learning  baseline  readers  on  AAQAD. Baseline readers as done in (Mozannar et al., 2019) apply for question  with  answers  for  ARCD  dataset  and  ArabicSQuAD. We modified baseline readers for AAQAD to add question with no answers. Each baseline reader generatesan answer for a question from the paragraph. They do by ranking every text span of length maximally 10 words in-side each sentence. 

# Non-Learning Baseline Models

- TF-IDF reader based on 4-gram features.

- Embedding fastText.

- Sliding Window Distance based reader.

- Random Guess.

## Author
- Eman Elrefai  [GitHub account](https://github.com/emanlotfy52)
