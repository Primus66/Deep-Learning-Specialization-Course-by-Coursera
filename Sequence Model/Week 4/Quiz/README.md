1.
Question 1
A Transformer Network, unlike its predecessors RNNs, GRUs and LSTMs, can process entire sentences all at the same time. (Parallel architecture).


True


2.
Question 2
The major innovation of the transformer architecture is combining the use of LSTMs and RNN sequential processing.


False


3.
Question 3
The concept of Self-Attention is that:

Given a word, its neighbouring words are used to compute its context by summing up the word values to map the Attention related to that given word.


Correct
4.
Question 4
What letter does the "{?}?" represent in the following representation of Attention?

Attention(Q, K, V) = softmax(\frac{QK^T}{\sqrt{d_?}})VAttention(Q,K,V)=softmax( 
d 
?
​
 
​
 
QK 
T
 
​
 )V



k


Correct
k is represented by the {?}? in the representation.

5.
Question 5
Which of the following statements represents Key (K) as used in the self-attention calculation?


K = qualities of words given a Q 


Correct
The qualities of words given a Q are represented by Key (K). 

6.
Question 6

ii here represents the computed attention weight matrix associated with the ithith “head” (sequence).

True


Correct
ii here represents the computed attention weight matrix associated with the ith “head” (sequence). 

7.
Question 7
Following is the architecture within a Transformer Network (without displaying positional encoding and output layers(s)).


What is generated from the output of the Decoder’s first block of Multi-Head Attention? 

Q


Correct
This first block’s output is used to generate the Q matrix for the next Multi-Head Attention block. 

8.
Question 8
Following is the architecture within a Transformer Network (without displaying positional encoding and output layers(s)).


What does the output of the encoder block contain?

Contextual semantic embedding and positional encoding information

Correct
The output of the encoder block contains contextual semantic embedding and positional encoding information.

9.
Question 9
Which of the following statements is true about positional encoding? Select all that apply.



Positional encoding is important because position and word order are essential in sentence construction of any language.

Correct
This is a correct answer, but other options are also correct. To review the concept watch the lecture Transformer Network.


Positional encoding provides extra information to our model.




10.
Question 10
Which of these is a good criterion for a good positionial encoding algorithm?


The algorithm should be able to generalize to longer sentences.

