# deeplearning-default-value
**WELCOME FOR YOUR PR!!**

## Functions

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
| dropout | ratio | [0.5](https://docs.chainer.org/en/stable/reference/generated/chainer.functions.dropout.html)| [0.5](https://pytorch.org/docs/stable/nn.html?highlight=dropou#torch.nn.functional.dropout)| [Required](https://www.tensorflow.org/api_docs/python/tf/nn/dropout)|

## Links

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
|Link  | initilizer | [LecunNormal](https://docs.chainer.org/en/stable/reference/initializers.html#weight-initializers)| Each link has <br> a different <br> initializer.| [GlorotUniform](https://www.tensorflow.org/api_docs/python/tf/get_variable)|

## Initializers
- PyTorch initializers are difined in each layer implementation, so skip it.

| Object names in Chainer | Parameter names in Chainer | Chainer     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:--------------:|
| GlorotUniform | scale | [1.0](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.GlorotNormal.html)| No args ([1.0](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/glorot_normal))|
| LecunNormal | scale | [1.0](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.LeCunNormal.html)| No args ([1.0](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/lecun_normal))|
| Normal | scale | [0.05](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.Normal.html)| [1.0](https://www.tensorflow.org/api_docs/python/tf/initializers/random_normal) or [0.05](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/RandomNormal)|
| Uniform | scale | [0.05](https://docs.chainer.org/en/stable/reference/generated/chainer.initializers.Uniform.html)|min, max = [(0.0, 1.0)](https://www.tensorflow.org/api_docs/python/tf/initializers/random_uniform) or [(-0.05, 0.05)](https://www.tensorflow.org/api_docs/python/tf/keras/initializers/RandomUniform)|

## Optimizers

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
| SGD | lr | [0.01](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.SGD.html) | [Required](https://pytorch.org/docs/stable/optim.html#torch.optim.SGD) |[0.01](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/SGD)|
| Adam | alpha | [0.001](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [0.001](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [0.001](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | beta1 | [0.9](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [0.9](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [0.9](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | beta2 | [1e-08](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [0.999](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [1e-08](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | eps | [1e-08](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [1e-08](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [1e-08](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | eta | [1.0](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [No args](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [No args](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | weight_decay | [0.0](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [0.0](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [No args](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|
|      | amsgrad | [False](https://docs.chainer.org/en/stable/reference/generated/chainer.optimizers.Adam.html) | [False](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [No args](https://www.tensorflow.org/api_docs/python/tf/train/AdamOptimizer)|

## Rules
### Kinds of symbols
- None: default value is None.
- x: No implementations.
- No args: Magic number. We can not specify the value.
- Required: No default value. We should specify the value.
