# SimpliLegal

## Legal Generator

LLama2 7b model is finetuned on a legal document that allows you to ask political, economic and socially informative as well as controversial questions. The model is consistent with its neutrality as no clear bias can be seen the resposes. 

## Legal Assistant

LLama2 7b model is used and RAG (Retrieval Augmented Generation) is leveraged to get outputs from the model on a specific topic, without having to be fine-tuned. Constitution of India is used as the database and the model uses vectorized search to find relevant information. It then stitches the relevant information with its own information to provide a coherent and context aware responses. This allows the model to maintain its generality along with focused generation of text on a particular topic, while expanding its knowledge base.
