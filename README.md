# Maximum-Likelihood-Estimation-From-Scratch

I implemented maximum likelihood estimation which is used in Natural Language Processing for predicting words in sentences.

How do we estimate N-gram probabilities?

We can use Maximum Likelihood Estimation to estimate the Bigram and Trigram probabilities. We get the MLE estimate for the parameters of an N-gram model by taking counts from a corpus, and normalizing them so they lie between 0 and 1.
For Bigram probability,
![image](https://user-images.githubusercontent.com/96420245/229370885-3a9e5d38-b90f-40d9-b102-c903a8e978d1.png)

Example:

![image](https://user-images.githubusercontent.com/96420245/229370894-e29969c6-b6dd-44a5-aaf9-8c995599dd19.png)

The bigram probability is calculated by dividing the number of times the string “prime minister” appears in the given corpus by the total number of times the word “prime” appears in the same corpus.
