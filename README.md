# pavlov-cli `v0.0.1`

The Pavlov CLI is a command line tool to train and automatically containerize models given a model specification, training hyperparameters, and a dataset. Currently only supports Caffe.

```
pavlov lenet --lr 0.001 --tag=mnist
```

## Installation
Simply run

`python setup.py install`

Now pavlov is in your path and can be run from anywhere. 

## Examples
to run the MNIST example, go to the project root and run

` ./examples/mnist/setup_mnist.sh `

then run

`pavlov lenet`
 
the model will train and save snapshots / intermediate model weights files to the `data/mnist` directory

## Contributors
- [@zan2434](http://github.com/zan2434)
