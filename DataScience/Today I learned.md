# Today I learned...

This is a running list to add to daily to track my progress.

## 2018

### August

| Date       | Today I learned...                             | Streak |
|:-----------|:-----------------------------------------------|   |
| **T&nbsp;09** | Got a tiny bit further with the **calculus for n00bs** chapter, I'll bring it to bed so that it will count fo realz. And I'll do a commit first. Oh! I learned how to fix the toilet seat back to the toilet after the new cleaner did such a good job that it came off 🚽 | 11 |
| **W&nbsp;08** | Today I started learning some **calculus** that I need to know to understand the math behind training a neural network. No commit tonight, I fell asleep instead.. | 10 |
| **T&nbsp;07** | I retrained my model using the **full dataset**, and accuracy jumped from 60% to close to 95% accuracy! After playing with the **number of nodes** and the **learning rate**, as well as adding more **epochs**, I managed an accuracy of 97.35%! That's a 2.65% error rate -- compared with the historical benchmarks here it's very very decent! http://yann.lecun.com/exdb/mnist/ | 9 |
| **M&nbsp;06** | Today I **trained my model!!** With only 100 datapoints to train it and a hidden layer of only 100 nodes, it guesses right 6 out of 10 times using the test data. Let's see tomorrow if we can improve on that :) `W00t!` | 8 |
| **S&nbsp;05** | Today I wrote the `train()` method of my `neuralNetwork` class. The last bit of math, where the network learns from errors by updating the weights between the layers, is still fuzzy to me. I've left it like that for now, I need to learn some calculus basics to understand it but wanted to get my hands in the code too badly... Next up: feeding it data to actually train my model! | 7 |
| **S&nbsp;04** | Today I worked more on the **neural network** I started coding last night before bed. https://github.com/rvoulon/my-first-neural-network | 6 |
|            | Also bought a keyboard and mouse and set up a new microSD with Nina for her Piper computer. We set up a new Raspbian install and next we want to do actual Python together. |   |
| **F&nbsp;03** | Today I actually understood something important about **gradient descent**. I'd already seen Andrew Ng's explanation about gradient descent but didn't get the point of it, and didn't understand why you needed it.. Usually gradient descent is explained with a visualization of some equation (with 2 or 3 dimensions), but I never understood why you needed something complicated like gradient descent to get the lowest value of *x* when you can just _point at it in the graph._ Why can't you just simply _solve the equation?_ | 5 |
|            | I finally understand why, it's because what was never mentioned is that those graphs with 2 or 3 dimensions are gross oversimplifications, because the actual equation is _n_-dimensional, it has as many dimensions as there are weights coming into a layer. So it's just utterly impossible to visualize, and mindblowingly difficult to solve. Therefore you need to use gradient descent to "gradually descend" down the slope of the graph until you've got a pretty close guess at the lowest value of x.  | 🤯 |
| **T&nbsp;02** | ...about **X** = **I** * **W**, where **X** is the matrix of all the moderated signals in a single layer of a neural network. **I** is the matrix of all the input signals coming from the previous layer (or coming into the input layer). **I** is moderated by **W**, the matrix of all the weights between this and the previous layer. After you've calculated **X**, you apply the sigmoid activation function to decide whether the signal is boosted enough to be sent to the next layer: output matrix **O** = sigmoid(**X**) | 4 |
|           | ...and also about **backpropagation**, where an error in the output (as compared to the training data) is used to adjust the weights proportionally, going back layer by layer until all weights have been adjusted. This is how the model is trained on the training data. |  |
| **W&nbsp;01** | ...about **sigmoid functions (logistic function)**, and multiplying **matrices**, and why it makes so much sense to express inputs and weights as matrices! (_Make Your Own Neural Network_)         | 3 |

### July

| Date       | Today I learned...                             | Streak |
|:-----------|:-----------------------------------------------|   |
| **T&nbsp;31**     | ...that a **loss** or **cost function** is really a function to describe the difference (error) between a predicted value and a real world value... | 2 |
|            | ...and that the **learning rate** is actually a fraction that moderates the change in parameters from one training example to the next, so that we don't lose the results from  all the previous training iterations.  (_Make Your Own Neural Network_) |   |
| **M&nbsp;30**     | ...how to set up **Github Pages**          | 1 |