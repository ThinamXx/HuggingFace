## **Hugging Face : Pipeline Function**

The [**Pipeline Function**](https://github.com/ThinamXx/HuggingFace/blob/main/02.%20Pipeline%20Function/PipelineFunction.ipynb) notebook is a comprehensive notebook as it contains all three steps of the **pipeline**: preprocessing with tokenizers, passing the inputs through the model, and postprocessing the outputs.  

**Note:**
- 📑[**Pipeline Function**](https://github.com/ThinamXx/HuggingFace/blob/main/02.%20Pipeline%20Function/PipelineFunction.ipynb) 

**Natural Language Processing**
- NLP is a field of linguistics and machine learning focused on understanding everything related to human language. The aim of NLP tasks is not only to understand single words individually, but to be able to understand the context of those words.

**Transformer Pipelines**
- The three main steps involved when we pass some text to a **pipeline** are:
  - The text is preprocessed into a format the model can understand.
  - The preprocessed inputs are passed to the model.
  - The predictions of the model are post-processed, so we can make sense of them.

**Preprocessing with Tokenizer**
- The tokenizer will be responsible for:
  - Splitting the input into words, subwords, or symbols like puncutation that are also called tokens.
  - Mapping each token to an integer.
  - Adding additional inputs that may be useful to the model.

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2027.PNG) 

**Going through Model**
- The vector output by the Transformer module is usually large. It generally has 3 dimensions:
  - Batch size: The number of sequences processed at a time.
  - Sequence length: The length of the numerical representation of the sequence.
  - Hidden size: The vector dimension of each model input.

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2027.PNG) 

