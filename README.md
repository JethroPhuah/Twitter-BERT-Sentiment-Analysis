# Twitter BERT Sentiment Analysis

I will be using the SMILE Twitter dataset. Performed exploratory analysis before performing sentiment analysis.

Tested with BERT pretrained model and tried fine-tuning it. However, the results of fine-tuning by adding/subtracting multiple layers did not turn out to be as great as expected. For example, adding 1 one more extra layer gives a F1 score of 0.768 while subtracting 2 layers gives me 0.7736. Multiple other experiments were conducted (thought I forgot to document them properly) but after several experiments, it seems like the number of layers do not have a direct relationship with the F1 score.

I have also tinkered with the batch sizes, dropout probability and the number of epochs. Finally with the pre-trained model, I found the best combination to get a F1 score of 0.887. The rest of the code and corresponding comments can be found in the ipynb file.