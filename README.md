# psychosis-symptom-keywords

Vocabularies and implementation details for the paper "Generating Positive Psychosis Symptom Keywords from Electronic Health Records" (Accepted at AIME 2019)

Available files:
* original_keywords: list of 26 seed terms used for vocabulary generation
* generated_terms: RT* terms from each vocabulary
* evaluation_results_unigram_models: all generated terms from unigram models (with manual classification)
* evaluation_results_bigram_models: all generated terms from bigram models (with manual classification)
* implementation_details: implementation details for embedding models

Manual classification of generated terms:
1) RT: relevant term
2) PT: potentially relevant term
3) NT: not relevant

RT*: terms classified as RT by at least one annotator
