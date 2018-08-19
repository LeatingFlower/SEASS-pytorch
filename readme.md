### Pytorch implementation for paper "Selective Encoding for Abstractive Sentence Summarization"
- author: Kirk
- mail: cotitan@outlook.com

### Requirments
- torch==0.4.0
- numpy==1.12.1+
- python=3.5+

### Noticement
1. ~~When running train.py, the console may print out EOFError or ConnectionResetError, which is caused by DataLoader module of pytorch. I don't know why but it does not influence the training process. Neglect It!~~ Set num_workers=0 (argument of DataLoader) to avoid this error messages.
2. This project haven't finish yet, there are bugs to be fix, and modules to be implement.

### How-to
1. Run _python train.py_ to train
2. Run _python mytest.py_ to generate summaries


### TODO
1. Implement maxout layer
2. ROUGE metric
3. Attention calculation
4. ~~Fix bugs on decoder~~ 
