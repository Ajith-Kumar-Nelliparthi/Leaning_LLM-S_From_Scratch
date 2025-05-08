## Learned LLM fundamentals, Positional Embeddings, Tokenization

- **Positional Embeddings**:
- Positional embeddings are a technique used in natural language processing (NLP) to incorporate the position of a word in a sentence into the input of a neural network. This is particularly useful in transformer-based models, where the input is a sequence of tokens (words or subwords) and the model needs to understand the order of these tokens.
- Positional embeddings are typically learned during training and are added to the input embeddings of each token.

- **Tokenization**:
- Tokenization is the process of breaking down text into individual words or tokens. This is a crucial step in NLP as it allows models to understand the structure and meaning of text.
- There are several tokenization techniques, including:
- **Word-level tokenization**: This involves splitting text into individual words. For example, "
- **Subword-level tokenization**: This involves splitting words into subwords or word pieces. For
- **Character-level tokenization**: This involves splitting text into individual characters.
- **Tokenization in LLMs**:
- LLMs typically use subword-level tokenization, which is more efficient and effective than word
- This is because subword-level tokenization can handle out-of-vocabulary (OOV) words
- **Tokenization in PyTorch**:
- PyTorch provides a built-in tokenizer called `BertTokenizer` that can be used to tokenize text 
- **Tokenization in Hugging Face Transformers**:
- Hugging Face Transformers provides a range of tokenizers, including `BertTokenizer`, `Rob
- **Tokenization in LLMs**:
- LLMs typically use subword-level tokenization, which is more efficient and effective than word 

- ## Finished Chapter 1,2 of [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch)

