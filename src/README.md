**Models:**
* RNN
* RNN with Luong Attention
* RNN with Bahdanau Attention
* CNN
* Transformer

**Parameters:**
* tokenizer = **underthesea**.word_tokenize
* optimizer = Adam(lr=0.001), NoamOpt (Transformer)
* loss = CrossEntropyLoss
* batch_size = 12 (greater may crash)
* epoch = 30 (≈ 2.5 hrs with kaggle GPU)
