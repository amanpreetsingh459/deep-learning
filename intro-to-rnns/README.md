# Anna KaRNNa

In this notebook, we'll build a character-wise RNN trained on Anna Karenina, a worth reading novel. It'll be able to generate new text based on the text from the book.

This network is based off of Andrej Karpathy's [post on RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) and [implementation in Torch](https://github.com/karpathy/char-rnn). Also, some information [here at r2rt](http://r2rt.com/recurrent-neural-networks-in-tensorflow-ii.html) and from [Sherjil Ozair](https://github.com/sherjilozair/char-rnn-tensorflow) on GitHub. Below is the general architecture of the character-wise RNN.

### Concepts Covered:
* Recurrent-Neural_Networks(RNNs)
* Long-Short Tems Memory cells(LSTMs) to deal with the problem of dying gradients
* Gradient clipping to deal with the problem of exploding gradients
* Drop-Out to regularize the network
* Adam-Optimizer

### Dependencies
The code uses tensorflow 1.0 version.

More learning Resources
Here are a few great resources for you to learn more about recurrent neural networks.

* Andrej Karpathy's [lecture on RNNs and LSTMs from CS231n](https://www.youtube.com/watch?v=iX5V1WpxxkY)
* Christopher Olah's [post on how LSTMs work](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* Little more advanced [implementation of RNNs in TensorFlow](http://r2rt.com/recurrent-neural-networks-in-tensorflow-i.html)

Hope you enjoy it...
