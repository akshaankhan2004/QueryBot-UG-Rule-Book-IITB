# QueryBot-UG-Rule-Book-IITB

Transformers from Hugging Face Library are used to load the pre-trained model and for further dataprocessing. 
The model uses RAG(Retrievel Augmented Generation) technique to extract data from UG-RuleBook and take inputs as queries and generate ouputs based on them. The generator llm taken is 'gpt2-large' and the retriever llm is "facebook/rag-sequence-nq". The total model parameters are around 1.2 Billion. The model is integrated with a gradio interface to make it user friendly.

# Problems
1. Better generation model was to be taken, with 7 Billion parameters,  instead of 'gpt2-large', but it couldn't be loaded due to computational restrictions.
2. Text in the UG-RuleBook was not arranged in the best format for this model, so its pre-processing was done, but it still needs better formatting.
   
Due to these reasons, the model is not able to give the best ouput to the user's queries.

# Model
GDrive link to the model- https://drive.google.com/drive/folders/1ttEwnwfRBr060lSSjO_MIzp-4ioPesGC?usp=share_link

Google Colab link-
https://colab.research.google.com/drive/1axcdnoLxfX9ybu52gYp6L5MwsGlMusmD?usp=sharing

# Instructions
Please edit the paths to various input files in the code accordingly.

To use the model:

1. Download all the files present in the Drive link.
2. Run 'gradio.ipynb' to use the model

# Notes
The file 'data_preprocessing.ipynb' was run in Google Colab and 'model.ipynb' was run in local system so there is some difference in both codes.




