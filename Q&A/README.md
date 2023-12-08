**Goal :** <br>
The goal of the project is to build a Question and Answer system powered by Large Language Models (LLM). 
The user uploads a research paper in the app and it will answer any specific question from the research paper.
<br>

**Data Required:** <br>
Digital copies of research papers in pdf format
<br>

**How to source the data?** <br>
The data can be sourced by scraping the internet for popular research papers
<br>


**Expected Results:** <br>
The app should reliably and correctly answer the questions using the information from the specific document.
<br> 

**Technology and Tools Used** <br>

1. Large Language Models (LLMs) <br>
   LLMS are deep learning models that are pre-trained on vast amounts of data and can be used for tasks like generating text, summarizing, translating, answering 
   questions etc.
    <br>
2. Retrieval Augmented Generation (RAG) <br>
   RAG is a technique that enhances the capabilties of LLMs by incorporating information retrieval into the text generation process. This is done by retrieving 
   data/documents relevant to a question or task and providing them as context for the LLM.
   <br>
3. LlamaIndex <br>
   LlamaIndex is an open source data framework for building RAG systems.
   <br>
4. Streamlit <br>
   Streamlit is an open source python library used to create custom web apps for ML
   <br>



**Results:** <br>
Based on the comparison of 2 different embedding models as well as 2 different LLMs for the RAG, the observations are:
1. Based on the evaluation results (context_precision and context_recall metrics) of the OpenAI model are the same as huggingface Bge embedding model in my RAG pipeline when applied to my own dataset.

2. The Zephyr model seems to outperform the Falcon model in my RAG pipeline when applied to my own dataset.
