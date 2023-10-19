# QueryBot-UG-Rule-Book-IITB
Please edit the paths to various input files in the code accordingly. Open 'gradio.ipynb' to directly use the model if all the files are downloaded from the link provided below.

Transformers from Hugging Face Library are used to load the pre-trained model and for further dataprocessing. 
The model uses RAG(Retrievel Augmented Generation) technique to extract data from UG-RuleBook and take inputs as queries and generate ouputs based on them. The generator llm taken is 'gpt2-large' and the retriever llm is "facebook/rag-sequence-nq". The total model parameters are around 1.2 Billion. The model is integrated with a gradio interface to make it user friendly.

# Problems
1. Better generation model was to be taken, with 7 Billion parameters,  instead of 'gpt2-large', but it couldn't be loaded due to computational restrictions.
2. Text in the UG-RuleBook was not arranged in the best format for this model, so its pre-processing was done, but it still needs better formatting.
   
Due to these reasons, the model is not able to give the best ouput to the user's queries.

# Model
GDrive link to the model- https://drive.google.com/drive/folders/130cwHu-DFVoRDNm0pwwfHmrCjZj16E4S?usp=share_link
