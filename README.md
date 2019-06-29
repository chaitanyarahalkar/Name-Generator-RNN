<h1 align="center">Welcome to Name Generator Using Recurrent Neural Networks 👋</h1>
<p>
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/chaitanyarahalkar/Name-Generator-RNN#README">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/kefranabg/readme-md-generator/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" target="_blank" />
  </a>
  <a href="https://github.com/chaitanyarahalkar/Name-Generator-RNN/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/chaitanyarahalkar/Name-Generator-RNN.svg" target="_blank" />
  </a>
  <a href="https://github.com/chaitanyarahalkar/Name-Generator-RNN/blob/master/LICENSE">
    <img alt="License: Apache-2.0" src="https://img.shields.io/github/license/chaitanyarahalkar/Name-Generator-RNN.svg" />
  </a>
  <a href="https://twitter.com/chairahalkar">
    <img alt="Twitter: chairahalkar" src="https://img.shields.io/twitter/follow/chairahalkar.svg?style=social" target="_blank"/>
  </a>
</p>

> A Recurrent Neural Network Model that generates human names based on existing data. The entire model is implemented from scratch, without using any deep learning framework like Pytorch, Tensorflow etc. 

### 🏠 [Homepage](https://github.com/chaitanyarahalkar/Name-Generator-RNN)

## Prerequisites 
- Numpy (Install with Pip)

## Usage

```sh
jupyter lab or jupyter-notebook
```

## Overview of the Model

The model will have the following structure: 
- Initialize parameters 
- Run the optimization loop
    - Forward propagation to compute the loss function
    - Backward propagation to compute the gradients with respect to the loss function
    - Clip the gradients to avoid exploding gradients
    - Using the gradients, update your parameter with the gradient descent update rule.
- Return the learned parameters 
    
<img src="rnn-2.png" style="width:450;height:300px;">

## Author

👤 **Chaitanya Rahalkar**

* Twitter: [@chairahalkar](https://twitter.com/chairahalkar)
* Github: [@chaitanyarahalkar](https://github.com/chaitanyarahalkar)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/chaitanyarahalkar/Name-Generator-RNN/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Chaitanya Rahalkar](https://github.com/chaitanyarahalkar).<br />
This project is [Apache-2.0](https://github.com/chaitanyarahalkar/Name-Generator-RNN/blob/master/LICENSE) licensed.

***
