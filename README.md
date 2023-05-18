# Question-Answer-Selection
This project utilizes pre-trained BERT model (Approach 1) and TF-IDF model (Approach 2) for Question-Answer selection process

## BERT model (Approach 1)
The first approach comprises of two models, the first model utilizes an information retrieval technique called TF-IDF to extract the top k paragraphs from the entire corpus based on a given query. The output of this model is then passed onto the second model, which is a context-based transformer pre-trained model known as BERT. BERT scores the context keywords to identify two most relevant answer paragraph.

## TF-IDF model (Approach 2)
The second approach uses TF-IDF twice to extract the relevant answer from the corpus. TF-IDF 1 selects the top 5 relevant paragraphs from the corpus in the first layer and refines this output by extracting the exact sentences from these paragraphs in the second layer.

