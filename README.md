# Open RAG From Scratch

This is a fork of [RAG From Scratch](https://github.com/langchain-ai/rag-from-scratch) that makes use of open local LLMs only (hosted using [Ollama](https://ollama.com/)).
It was created to allow following [this tutorial](https://www.youtube.com/watch?v=sVcwVQRHIc8) using only local models and without any API key requirements.

All credits for the original repository go to [rlancemartin](https://github.com/rlancemartin).

So far, the following notebook has been modified to use only Ollama models and local functions:
The notebooks have been adapted to use only Ollama models and to not require any API keys.
Additionally, chains have been adapted to be used with reasoning models too, excluding the parts within the `<think></think>` tags.

This is an ongoing project: not all notebooks have been adapted yet.
Current progress:
- [x] `rag_from_scratch_01_to_04.ipynb`
- [x] `rag_from_scratch_05_to_09.ipynb`
- [ ] `rag_from_scratch_10_and_11.ipynb`
- [ ] `rag_from_scratch_12_to_14.ipynb`
- [ ] `rag_from_scratch_15_to_18.ipynb`

For any issues, feel free to open a [Github issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues).