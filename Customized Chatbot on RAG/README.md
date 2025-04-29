Project Summary

In this project, I will using RAG and GPT 3.5, whose knowledge is up to 2021, to build a Chatbot that is aware of 2024 US Presidential Election. Specifically, I will:

* Load GPT model and verify its unawareness of 2024 presidential election.
* Call Wikipedia API to fetch 2024 presidential election data and generate embeddings of each sentence.
* Compare the similarities between user input and knowledge base, return the top K results as context.
* Combining context and user input as prompt, ask GPT model to return the accurate answers.
