# rag-baseline-pipeline
A Step-by-Step Guide Using Open-Source Models to Generate a Novelist Advisor Inspired by Orhan Pamuk.

# Introduction
A baseline solution is established to implement an end-to-end RAG pipeline using YouTube videos. All the resources that are used in this application are open-source. So, you don't need any API key or pay for any service. 

This project is generated as a baseline solution (using company data) for our GenAI iterations.

P.S. This solution has been implemented in Mac. So, there might be some inconsistencies on the other platforms since this code has not been tested on another environment. If you face it, please let me know! :)

# How
You can find all the details in the [blog post](https://medium.com/numberly-tech-blog/build-your-rag-pipeline-a-step-by-step-guide-using-open-source-models-to-generate-a-novelist-7f2ca52cfbf3)!

Installation of the packages:

```commandline
pip install -r requirements.txt
```

After you install all the packages, you can run the [notebook file](app.ipynb).

Initially, you can install YouTube videos and then process them as pickle file. For the further iterations, you can use these pre-processed pickle files to save time!

To access all open-source sentence-transformers (embedding generation), you can visit:
https://huggingface.co/sentence-transformers

To access all open-source LLMs, you can visit:
https://huggingface.co/models?pipeline_tag=text-generation
