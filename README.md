# Chat bot for customer service using LLMA 

The notebook contains basic customer service data in text format to train Llama model using the provided information. Llama is an open-source LLM model developed by Meta starting in Feb 2023. I have built a chat bot using RAG (retrieval-augmented generation) means only limiting the responses and answering the questions depending on the document information. With limited examples of data or information, one can use RAG/prompt engineering to get the desired response. You can control the randomness of the response generation using temperature parameter (lower the temperature, less randomness in response generation).

These are foundational prompting techniques that generate impressive results from large language models (LLMs) without any training or fine-tuning.
1. Zero-shot prompting - Ask the questions directly without any training
2. Few-shot prompting - provide a few examples of the task before asking the model to do it
3. Chain-of-thought prompting - Encourage step-by-step logic and generate the response.
