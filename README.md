<h1 style="text-align: center;">NLP Final Project: Fine Tune Bert</h1>
<h4 style="text-align: center;">Application of Different Fine tuning Techniques<br>Chantel Walia<br>Vaishak Menon</h4>
<h4 style="text-align: center;"></h4>

### Project Description

Original Paper: <a href="https://arxiv.org/abs/1905.05583">How to Fine-Tune BERT for Text Classiﬁcation?</a>

Based on the original paper, we took the base-bert-uncased model and tried to replicate the original results. There were three types of text classification that was tested. 

- Vaishak worked on Sentiment Analysis. 
- Chantel Worked on Topic Classification.
- Both team members tried to work on Question Classification but were unable to fully complete it.

Datasets exist on Cheaha for Vaishak's server for Question Classification and Sentiment Analysis

Used Datasets:

- IMDB
- Yahoo
- TREC
- AG News

General code creation and testing process went along the lines of create a base model to run each dataset. Then update the model with one of the 4 fine tuning techniques. After updating the model, run the code again on the new model or processed data.

4 Techniques:
- Head-Tail Truncation
- Catastrophic Forgetting
- Features from Different Layers
- Layer-wise Decreasing Learning Rates

### How to Run

Ensure that the nlp2023v2.yml file is downloaded and used for the kernel envirornment.

In order to run the code for Sentiment Analysis, open the Jupyter Notetbook that is available in the repository. Open the aclimdb_v1.tar.gz within the datasets folder. After extracting all of the data from the tar.gz file, ensure that all data is in the datasets folder underneath the the directory that the data exists from. For example for the IMDB database, the directory should look like "datasets/aclimdb/...". If all of the data has been downloaded correctly, next just run all of the cells in order and the code should provide outputs. There should be a cell available to extract the tar.gz file for each code file but if not extracting them does not take long.

For Question Classification, the same process can be applied from Sentiment Analysis. Ensure that the Yahoo dataset is downloaded in the same fasion and has the same path. The TREC dataset is downloaded using dataset library from Hugging Face.

### References

Code was generated using ChatGPT; All references to ChatGPT for code is provided for each ipynb file within that file.