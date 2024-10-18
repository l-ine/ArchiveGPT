# ArchiveGPT
Using a multimodal LLM in archives

### Notebook *prompting_pipeline.ipynb*

It loads the multimodal model *InternVL2-Llama3-76B* and uses it for inference.

A prompt can be specified. Using the prompt, image descriptions of example images (input folder *images*) are generated and saved into a csv (output folder *responses*, currently empty).

##### in:

- prompt string specified in the notebook
- images in folder *images*

Images are examples provided by InternVL Chat:
https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat/examples

##### out:

*responses.csv* in folder *responses* (currently empty)
