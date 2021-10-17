# CNN-for-text-classification-in-PyTorch
Text Classification Using Convolutional Neural Network (CNN) :
CNN is a class of deep, feed-forward artificial neural networks ( where connections between nodes do not form a cycle) & use a variation of multilayer perceptrons designed to require minimal preprocessing. These are inspired by animal visual cortex.
I have taken reference from Yoon Kim paper.
https://acadpubl.eu/hub/2018-119-15/4/766.pdf
CNNs are generally used in computer vision, however they’ve recently been applied to various NLP tasks and the results were promising.
Let’s briefly see what happens when we use CNN on text data through a diagram.The result of each convolution will fire when a special pattern is detected. By varying the size of the kernels and concatenating their outputs, you’re allowing yourself to detect patterns of multiples sizes (2, 3, or 5 adjacent words).Patterns could be expressions (word ngrams?) like “I hate”, “very good” and therefore CNNs can identify them in the sentence regardless of their position.
![](https://miro.medium.com/max/1838/0*0efgxnFIaLTZ2qkY)
