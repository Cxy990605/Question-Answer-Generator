### Why Transformer?

* The Transformer in NLP is a novel architecture that aims to solve sequence-to-sequence tasks while handling long-range dependencies with ease. It relies entirely on **self-attention** to compute representations of its input and output WITHOUT using sequence-aligned RNNs or convolution.
  
---
### What makes it different?
* This fine-tuned model has been extend to **Chinese** and **Multilingual** dataset, and hence it becomes a Bilingual QA generator.

---
### What are the potential Applications?
* Q&A Chatbot
* Quiz Creator
* Essay summary
  
---
### Results
<img width="542" alt="Screen Shot 2024-04-13 at 7 13 33 PM" src="https://github.com/Cxy990605/Question-Answer-Generator/assets/99168940/b7eeae1a-da93-4e8f-afcb-dc3225e56556">

---
Reference:

* Attention Is All You Need[^1]
* Data-QuestEval: A Referenceless Metric for Data-to-Text Semantic Evaluation[^2]



[^1]: <https://arxiv.org/abs/1706.03762>
[^2]: <https://arxiv.org/abs/2104.07555>  


HuggingFace:
* Transformer[^note]

[^note]: <https://huggingface.co/docs/transformers/en/index>
