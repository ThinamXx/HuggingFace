## **Hugging Face : Tokenizers & Models**

The [**Tokenizers & Models**](https://github.com/ThinamXx/HuggingFace/blob/main/03.%20Tokenizers%20%26%20Models/Models%26Tokenizers.ipynb) notebook contains the comprehensive information about the basic buildings blocks of a Transformer model, tokenization pipeline, limitations of input IDs, attention masks, and configurable tokenizer methods. 

**Note:**
- 📑[**Tokenizers & Models**](https://github.com/ThinamXx/HuggingFace/blob/main/03.%20Tokenizers%20%26%20Models/Models%26Tokenizers.ipynb)

**Tokenizers**
- The basic type of tokenizer that comes to mind is word-based tokenizer. It's generally very easy to set up and use with only a few rules, and it yeilds decent results.

**Subword Tokenization**
- Subword Tokenization rely on the principle that frequently used words should not be split into smaller subwords, but rare words should be decomposed into meaningful subwords.

**Encoding**
- Translating text to numbers is known as encoding. Encoding is done in a two-step process: the tokenization, followed by the conversion to input IDs.
- Batching is the act of sending multiple sentences through the model, all at once. If we have only one sentence, we can just build a batch with a single sequence.
- Padding makes sure all our sentences have the same length by adding a special word called the padding token to the sentences with fewer values.

**Attention Masks**
- Attention masks are tensors with the same shapes as the input IDs tensors, filled with 0s and 1s: 1s indicate the corresponding tokens should be attended to, and 0s indicate the corresponding tokens should not be attended to i.e. they should be ignored by the attention layers of the model.

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2029.PNG)

![Image](https://github.com/ThinamXx/MachineLearning_DeepLearning/blob/main/Images/Day%2030.PNG)
