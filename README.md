# GPT-Model
GPT Model trained on tiny-Shakespeare data

The model is trained to generate text for the length provided resembling Shakespeare's text. 

Key Components of the model are:
- Word embedding
- Positional encoding
- Multi-headed self-attention (No cross attention)
- Transformer Decoder block (No Encoder since it is generating text on its own)


Training and Model parameters: 
- The model uses character-level tokens
- total number of tokens in the dataset ~ 1 Million
- Number of transformer blocks used - 6
- Number of multi-attention heads - 8
- learning rate - 3e-4
- Number of embeddings - 384
- Block size - 256
- batch-size - 64
