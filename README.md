# useful-llm-articles
A collection of useful LLM (or related) articles, blog posts, papers, concepts, etc.

## Fine-tuning

* [LoRA](https://www.databricks.com/blog/efficient-fine-tuning-lora-guide-llms) - Low-rank adaptation (LoRA) is a technique for fine-tuning large language models (LLMs) that involves breaking down changes made to the model's weight matrix into two lower-rank matrices, A and B. This decomposition reduces computational overhead while preserving the model's learning capability. LoRA leaves the pretrained layers of the LLM fixed and adds a trainable rank decomposition matrix into each layer of the model. 

* [QLoRA](https://arxiv.org/abs/2305.14314) - A more memory-efficient version of LoRA.

## Retrieval-Augmented Generation (RAG)

* **Hierarchical Retriever/Clustered Search**

  1.  The first level of search decides which group of PDF’s to look at. A group at this level could be based on sub-topics.
  2.  The second level of search decides which specific PDF to look at.
  3.  The third level of search decides which specific chunks to use for the context.
  An architecture like this will drastically reduce the compute complexity of the retrieval task and save you time.


