## Search and indexing your own Google Drive Files using GPT3, LangChain, and Python.

The jupyter notebook included here will enable you to build a FAISS index on your document corpus of interest, and search it using semantic search. Details of this flowchart are described in https://medium.com/@venuv62/can-chatgpt-be-your-bff-code-companion-4375fd73ec3a. 


![image](https://user-images.githubusercontent.com/1031925/217168553-d74ef962-1a9d-4351-8c96-9033e65d58ab.png)

I've provided a test directory of Neuromodulation papers if you want to as a sample Drive folder to test against -  https://drive.google.com/drive/folders/1eIBnSO7MVOW9-BKPCJhs7JuBDRyXPOFC?usp=sharing

I will be working on a few enhancements to speed up the indexing (perhaps using a Vectorstore) and to optimize the query cost (using ideas from https://gpt-index.readthedocs.io/en/latest/how_to/cost_analysis.html)
