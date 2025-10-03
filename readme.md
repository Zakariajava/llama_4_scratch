# llama_4_scratch

This project is a **from-scratch implementation and explanation** of key components of a LLaMA-style transformer.  
replicate the structure of the [video tutorial](https://www.youtube.com/watch?v=wcDV3l4CD14), I went further by **explaining each function, part, and operation in detail** with clear examples and comments.

---

## 📚 What I Did

I broke the implementation into several notebooks, each focusing on one core part of the architecture:

### 🔹 Tokenizer (`llama_4_Tokenizer.ipynb`)
- Built a simple tokenizer to map text → tokens → IDs and back.  
- Explained how vocabularies work with examples of encoding/decoding.  
- Added step-by-step comments to clarify how tokens are handled.

### 🔹 Attention Mechanism (`attention_mechanism.ipynb`)
- Implemented **scaled dot-product attention** with Queries, Keys, and Values.  
- Showed how attention scores are calculated and turned into probabilities.  
- Added toy examples and visualizations so you can see which token attends to which.

### 🔹 Multi-Head Latent Attention (`llama_4_Multi-Head-Latent-Attention_explanation.ipynb`)
- Extended single attention to **multi-head attention**.  
- Explained how multiple heads run in parallel and then combine their outputs.  
- Described the “latent” part: how hidden representations evolve across layers.  
- Walked through the forward pass with detailed comments and examples.
