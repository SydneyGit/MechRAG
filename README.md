# MechRAG
MechRAG is a Large Language Model (LLM)-based augmented tool for mechanical engineering. It features capabilities of analyzing mechanical engineering data from local storage with the general knowledge obtained from the pre-training of LLMs. 


The notebooks are used for:
  1) Text tasks: MechRAG_textTask_Claude.ipynb (MechRAG_textTask_Claude_git.ipynb is the same code but processed for github rendering if MechRAG_textTask_Claude.ipynb does not work properly)
  2) Multi-modal tasks: MechRAG_MutltimodalTask_GPT.ipynb (MechRAG_MutltimodalTask_GPT_git.ipynb is the same code but processed for github rendering if MechRAG_MutltimodalTask_GPT.ipynb does not work properly)


 
To use the notebooks:
1. download notebooks and datasets. The notebooks are the easiest to run on Google Colab
2. fill in the gaps in the code for:
    1) API keys
    2) address of the datasets/current working directory/...



To quickly run the notebooks, the smaller versions of the datasets are here:
  1) vectorstore_1%perClass.npz, vectorstore_2%perClass.npz, are for MechRAG_MutltimodalTask_GPT.ipynb
  2)  vectorstore_0.5%.npz, vectorstore_1%.npz, are for MechRAG_textTask_Claude.ipynb
