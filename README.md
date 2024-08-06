# Llama-3-8B-Fine-tune

This repository demonstrates the fine-tuning of the Llama-3-8B model and compares its performance with the base model. It is part of a comparative study between fine-tuning and Retrieval-Augmented Generation (RAG) to determine which approach is more suitable for our use case.

The detailed blog can be found [here](https://medium.com/@siddheshraw/389554dd1f64).


Fine_tuning.ipynb contains all the code necessary for fine-tuning the model.


### Dataset
For this project, we will be using publicly available medical data. This dataset is structured as prompt-completion pairs, where users ask medical questions and receive relevant responses from doctors. ([Data Source](https://github.com/Kent0n-Li/ChatDoctor/blob/main/README.md))

You can access the fine-tuned model on Hugging Face via this [link](https://huggingface.co/Sid404/Llama-3-8B-bnb-4bit-medical_LoRA/tree/main).


For questions or feedback about the project, don't hesitate to reach out to me on [LinkedIn](https://www.linkedin.com/in/siddhesh-sreedar/).


**The RAG implementation for this study can be found [here](https://github.com/Siddhesh19991/RAG_Medical_Data).**
