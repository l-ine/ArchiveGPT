# ArchiveGPT
Using a multimodal LLM in archives

### Notebook *prompting_pipeline.ipynb*

It loads the multimodal model *InternVL2-Llama3-76B* and uses it for inference.

A prompt can be specified, asking to create an archival catalogue entry with the given image. Using the prompt and images (input folder *images*), one text per image is generated and saved into a *.csv* file (output folder *responses*, currently empty).

##### in:

- prompt string specified in the notebook
- images in folder *images*

Currently, images are examples provided by InternVL Chat and do not have any archival context:
https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat/examples

##### out:

- *responses.csv* in folder *responses* (currently empty)
