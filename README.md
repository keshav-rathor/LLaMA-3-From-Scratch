# LLaMA-3-From-Scratch
**🚀 Overview: Recreating LLaMA 3 (Simplified, CPU-Only)**
Following the success of your previous Medium blog where you built a 2.3M parameter LLM from scratch using LLaMA architecture, this blog focuses on recreating LLaMA 3 in a simplified, CPU-only setup.


![1*B0lqXfMVjMmBQyShIZei2g](https://github.com/user-attachments/assets/ae7e8a2a-32fb-4df1-bd9b-d960acf1bedb)

| **Feature**                                           | **LLaMA 3**                                                 | **LLaMA 2**                                            |
| ----------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------ |
| **Tokenizer**                                         | `tiktoken` (by OpenAI)                                      | `SentencePiece`                                        |
| **Number of Parameters**                              | 8B, 70B                                                     | 7B, 13B, 70B                                           |
| **Training Data**                                     | 15T tokens                                                  | 2.2T tokens                                            |
| **Context Length**                                    | 8192 tokens                                                 | 4096 tokens                                            |
| **Attention Mechanism**                               | Grouped-query attention                                     | Grouped-query attention                                |
| **Fine-Tuned Models Available**                       | Yes                                                         | Yes                                                    |
| **Performance**                                       | Outperforms LLaMA 2 on all benchmarks                       | Outperforms LLaMA 1 on most benchmarks                 |
| **Computational Requirements**                        | Very high (especially 70B)                                  | Very high (especially 70B)                             |
| **Availability**                                      | Open source                                                 | Open source                                            |
| **Reinforcement Learning from Human Feedback (RLHF)** | Yes                                                         | Yes                                                    |
| **Languages Supported**                               | 30 languages                                                | 20 languages                                           |
| **Suitable For**                                      | Most demanding tasks (reasoning, coding, proficiency tests) | Demanding tasks (reasoning, coding, proficiency tests) |




**🛠 System Requirements:**

* **Accelerator:** CPU-only
* **RAM:** Minimum 17 GB
* **Alternative:** Use **Kaggle** (30 GB RAM, no GPU required)

**📌 Prerequisites:**

* Understanding the **difference between LLaMA 2 and LLaMA 3**
* Familiarity with **Transformer architecture**
* Key concepts:

  * **RMSNorm (Pre-normalization)**
  * **SwiGLU activation**
  * **RoPE (Rotary Positional Embeddings)**
  * **Byte Pair Encoding (BPE)**

**🧱 Project Structure & Implementation Steps:**

1. **Understand the file structure**
2. **Tokenize input data**
3. **Create embeddings for each token**
4. **Apply RMSNorm**
5. **Build attention mechanism**

   * Queries, Keys, Values
   * RoPE
   * Self-Attention
   * Multi-Head Attention
6. **Implement SwiGLU activation**
7. **Merge all components**
8. **Generate the final output**

**📄 Reference:**
👉 [2.3+ Million Parameter LLM From Scratch (Medium Blog)](https://medium.com/)

---

