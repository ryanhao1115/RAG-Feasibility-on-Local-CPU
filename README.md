# RAG-Feasibility-on-Local-CPU
Feasibility Study on Implementing RAG on Local CPU Infrastructure

###Objective
In the current environment where large models are gaining significant attention, Retrieval-Augmented Generation (RAG) has become the most popular choice for enterprise applications. This is not only because it eliminates the need to retrain large models, but also, based on my years of experience in enterprise data analysis, many companies are deeply concerned about uploading sensitive internal data to the cloud for model training. As a result, running RAG locally is an excellent option.

Additionally, with the skyrocketing prices of GPUs, many enterprises find that their existing data centers have substantial unused computational power. Therefore, running RAG on local CPUs is also a viable alternative. With this in mind, I plan to test RAG using different model combinations to evaluate its feasibility for practical applications.

###Test Case 1
Model Sources

Model Components

Testing Method:
Single-document Q&A. A PDF financial report will be used as the local dataset.
