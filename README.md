# A-comparison-between-Abstractive-and-Semi-Abstractive-methods-for-text-summarization-on-the-CNN-Dail

MSc Thesis - Research Project

In this day and age, there is an enormous amount of textual material, and it is only
growing every single day. There is a great need to reduce much of this text data to
shorter, focused summaries that capture the salient details.
The main goal of this research is to examine what type of summaries do human
users prefer. Thus, we compare the performance of a straightforward Attention-
Based Encoder-Decoder abstractive summarization method, against a hybrid model
that rstly detects the most important parts of the original document, and then uses
paraphrasing in order to create a novel summary, on the non-anonymized version of
the CNN/Daily dataset. Besides ROUGE, that is being used as a baseline automatic
evaluation metric, we conduct a human evaluation experiment in order to assess the
Readability and Relevance of the output summaries of our two main models, three
extractive baseline models and reference summaries. The level of correlation of
ROUGE and Human Evaluation results is being measured alongside with the level
of abstractiveness of the models' outputs.
Both ROUGE and Human Evaluation results indicate that the abstractive approach
outperforms the hybrid method. However, the correlation analysis showcases that
the automatic and human evaluation results have no relationship. Furthermore, our
abstractiveness results showcase that both models tend not to use novel words, but
rather copy from the original text, which can be explained by the low abstractiveness
scores of the reference summaries on which our models are trained, a fact that makes
the appropriateness of the CNN/Daily Mail dataset for the task highly questionable.
Through this study, we argue that despite that ROUGE can be useful to quickly
assess the quality of a summary, it mainly provides information regarding its informativeness.
However, there are more things to consider when evaluating a summary
such as text's 
uency, grammaticality, factual accuracy, completeness, length and
abstractiveness.
