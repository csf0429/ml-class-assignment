#Week4 Exercise
##Non-linear Hypotheses
>Suppose you are learning to recognize cars from 100×100 pixel images (grayscale, not RGB). Let the features be pixel intensity values. If you train logistic regression including all the quadratic terms (<math><msub>
<mi>x</mi><mi>i</mi></msub><msub><mi>x</mi><mi>j</mi></msub></math>)as features, about how many features will you have?

The answer is: 50million(<math><mn>5</mn><mo>*</mo><msup><mn>10</mn><mn>7</mn></sup></math>)
  
    100*100 + 100*100 + C(100*100,2) = 50015000
    10000   + 10000   + 49995000     = 50015000
    xi         xi^2       xixj
    
    
    
  
  
  
##Test Neural Network: Representation
####1.which of the following statements are true?Check all that apply.

A. Suppose you have a multi-class classification problem with three classes, trained with a 3 layer network. Let a(3)1=(hΘ(x))1 be the activation of the first output unit, and similarly a(3)2=(hΘ(x))2 and a(3)3=(hΘ(x))3. Then for any input x, it must be the case that a(3)1+a(3)2+a(3)3=1.  


B.In a neural network with many layers, we think of each successive layer as being able to use the earlier layers as features, so as to be able to compute increasingly complex functions.
>解析：Correct.

C.If a neural network is overfitting the data, one solution would be to decrease the regularization parameter λ.
>解析：Wrong. If a neural network is overfitting the data, one solution would be to increase the regularization parameter λ.

D.If a neural network is overfitting the data, one solution would be to increase the regularization parameter λ.
>解析：Correct.

####5.You are using the neural network pictured below and have learned the parameters Θ(1)=<math><mfenced open="[" close="]"><mtable><mtr><mtd><mn>1</mn></mtd><mtd><mn>2.1</mn></mtd><mtd><mn> 1.3</mn></mtd></mtr><mtr><mtd><mn>1</mn></mtd><mtd><mn>0.6</mn></mtd><mtd><mn>-1.2</mn></mtd></mtr></mtable></math>(used to compute a(2)) and Θ(2)=<math><mfenced open="[" close="]"><mtable><mtr><mtd><mn>1</mn></mtd><mtd><mn>4.5</mn></mtd><mtd><mn> 3.1</mn></mtd></mtr></mtable></math> (used to compute a(3)} as a function of a(2)). Suppose you swap the parameters for the first hidden layer between its two units so Θ(1)=<math><mfenced open="[" close="]"><mtable><mtr><mtd><mn>1</mn></mtd><mtd><mn>0.6</mn></mtd><mtd><mn>-1.2</mn></mtd></mtr><mtr><mtd><mn>1</mn></mtd><mtd><mn>2.1</mn></mtd><mtd><mn>1.3</mn></mtd></mtr></mtable></math> and also swap the output layer so Θ(2)=<math><mfenced open="[" close="]"><mtable><mtr><mtd><mn>1</mn></mtd><mtd><mn>3.1</mn></mtd><mtd><mn> 4.5</mn></mtd></mtr></mtable></math>. How will this change the value of the output hΘ(x)?

A.It will stay the same.
>解析：Correct.  

B.It will increase.  
C.It will decrese.  
D.Insufficient information to tell:it may increase or decrease.



