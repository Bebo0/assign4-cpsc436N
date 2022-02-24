# assign4-cpsc436N

# Instructions:

# (PART-1: Traditional: HMM)
## Q1 (Further processing the dataset, state, and observation list) 

- (a) [20pts]: Fixing the state list
- (b) [15pts]: Adding comments
## Q2 [15pts]:  (Computing the Emission Probabilities) The emission probability matrix can be formed as a dictionary, please try to understand the structure of this dictionary and complete the following code to obtain the emission probability matrix with a final normalization+smoothing step.

- Please do the same in the code for computing the transition probabilities.

## Q3 [15pts]: (Implementing the Viterbi Algorithm) Please add comments to the lines with "COMMENT NEEDED" explaining what each corresponding line is doing. 

## Q4 [10pts]: (Apply the Viterbi Algorithm) Remember to deal with unknown words and report the tagging results.

#(PART-2: Neural: Bidirectional Stacked LSTM)
##Q5 [10pts]: (Construct word-to-index and tag-to-index mapping dictionary) Add comments to the lines with "COMMENT NEEDED" to code dealing with unknown tokens in testing
##Q6 [15pts]: (Design the architecture of the bidirectional stacked LSTM-based POS tagger - Initialize and Train the model) Add comments to the lines with "COMMENT NEEDED" explaining what each corresponding line is doing. 

##Q7 [15pts]: (Test the model) train and test a different model with a dropout rate of 0.05. Report the performance and a plausible explanation for the different performance of the two tested models (if any).


# Useful resources:

- https://stats.stackexchange.com/questions/289369/log-probabilities-in-reference-to-softmax-classifier
- https://discuss.pytorch.org/t/logsoftmax-vs-softmax/21386
- https://datascience.stackexchange.com/questions/40714/what-is-the-advantage-of-using-log-softmax-instead-of-softmax
- https://towardsdatascience.com/simplified-math-behind-dropout-in-deep-learning-6d50f3f47275
- https://stackoverflow.com/questions/65192475/pytorch-logsoftmax-vs-softmax-for-crossentropyloss
- https://stackoverflow.com/questions/41455101/what-is-the-meaning-of-the-word-logits-in-tensorflow
- https://jamesmccaffrey.wordpress.com/2020/06/11/pytorch-crossentropyloss-vs-nllloss-cross-entropy-loss-vs-negative-log-likelihood-loss/
