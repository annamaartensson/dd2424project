# Jane Austen Text Generation

## About the project
The purpose of this project was to create and train a model capable of capturing and emulating the nuances of Jane Austen's writing. Several model architectures and tokenization techniques were explored and compared in terms of performance on a test set and quality of text generated. The data for training and testing is based on the works of Jane Austen as sourced from Project Gutenberg.

### Models
- Vanilla Recurrent Neural Network (RNN)
- One-layer Long-Short-Term-Memory (LSTM)
- Two-layer Long-Short-Term-Memory (LSTM)

### Tokenization
- Character-level
- Word-level, using word2vec embedding
- Subword-level, using Byte-Pair Encoding (BPE)
