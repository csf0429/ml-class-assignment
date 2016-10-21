#Week4
###Non-linear Hypotheses
>Suppose you are learning to recognize cars from 100×100 pixel images (grayscale, not RGB). Let the features be pixel intensity values. If you train logistic regression including all the quadratic terms (<math><msub>
<mi>x</mi><mi>i</mi></msub><msub><mi>x</mi><mi>j</mi></msub></math>)as features, about how many features will you have?

The answer is: 50million(<math><mn>5</mn><mo>*</mo><msup><mn>10</mn><mn>7</mn></sup></math>)
  
    100*100 + 100*100 + C(100*100,2) = 50015000
    10000   + 10000   + 49995000     = 50015000
    xi         xi^2       xixj