1. What does a neuron compute?
 Ans: A neuron computes a linear function (z = Wx + b) followed by an activation function


2. Which of these is the "Logistic Loss"?

 Ans: L(i)(y^(i),y(i))=−(y(i)log⁡(y^(i))+(1−y(i))log⁡(1−y^(i)))


3. Suppose img is a (32,32,3) array, representing a 32x32 image with 3 color channels red, green and blue. How do you reshape this into a column vector?

 Ans: x = img.reshape((32323,1))


4. Consider the two following random arrays "a" and "b":
What will be the shape of "c"?

 Ans: c.shape = (2, 3)


5. Consider the two following random arrays "a" and "b":
What will be the shape of "c"?

 Ans: The computation cannot happen because the sizes don't match. It's going to be "Error"!


6. Suppose you have nxn_xnx input features per example. Recall that X=[x(1)x(2)...x(m)]X = [x^{(1)} x^{(2)} ... x^{(m)}]X=[x(1)x(2)...x(m)]. What is the dimension of X?

 Ans: (nx,m)


7. Recall that "np.dot(a,b)" performs a matrix multiplication on a and b, whereas "a*b" performs an element-wise multiplication.
Consider the two following random arrays "a" and "b":
What is the shape of c?

 Ans: c.shape = (12288, 45)


8. Consider the following code snippet:
How do you vectorize this?

 Ans: c = a + b.T


9. Consider the following code:
What will be c? (If you’re not sure, feel free to run this in python to find out).

 Ans: This will invoke broadcasting, so b is copied three times to become (3,3), and ∗*∗ is an element-wise product so c.shape will be (3, 3)


10. Consider the following computation graph.
What is the output J?

 Ans: J = (a - 1) * (b + c)
