## **Hugging Face : Fine Tuning Pretrained Models**

The [**Pretrained Models**](https://github.com/ThinamXx/HuggingFace/blob/main/04.%20Pretrained%20Models/PretrainedModel.ipynb) notebook contains information about Preprocessing the Dataset, Dynamic Padding, Training & Evaluation of 🤗 Transformer Models. 

**Note:**
- 📑[**Pretrained Models**](https://github.com/ThinamXx/HuggingFace/blob/main/04.%20Pretrained%20Models/PretrainedModel.ipynb)

**MRPC (Microsoft Research Paraphrase Corpus)**
- In this notebook, we will use MRPC (Microsoft Research Paraphrase Corpus) dataset introduced by William B. Dolan and Chris Brockett. The dataset consist of 5801 pairs of sentences, with a label indicating if they are paraphrases or not. It is one of the 10 datasets composing the GLUE benchmark, which is an academic benchmark that is used to measure the performance of ML models across 10 different text classification tasks.

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2031a.PNG) 

**Dynamic Padding**
- The function that is responsible for putting together samples inside a batch is called a collate function. Dynamic Padding means the samples in the batch should all be padded to the maximum length inside the batch. I have presented the implementation of Tokenization Pipeline & Training here in the snapshot.

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2031b.PNG)
