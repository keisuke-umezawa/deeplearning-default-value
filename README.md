# deeplearning-default-value

## Functions

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
| dropout | ratio | [0.5](https://docs.chainer.org/en/stable/reference/generated/chainer.functions.dropout.html)| [0.5](https://pytorch.org/docs/stable/nn.html?highlight=dropou#torch.nn.functional.dropout)| [None](https://www.tensorflow.org/api_docs/python/tf/nn/dropout)|

## Links

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     |
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
|Link  | initilizer | [LecunNormal](https://docs.chainer.org/en/stable/reference/initializers.html#weight-initializers)| Each link has <br> a different <br> initializer.| [GlorotUniform](https://www.tensorflow.org/api_docs/python/tf/get_variable)|

## Initializers

| Object names in Chainer | Parameter names in Chainer | Chainer     | PyTorch     | TensorFlow     | 
|:----------------------- |:---------------------------|:-----------:|:-----------:|:--------------:|
| LecunNormal             | scale                      |          1.0|            x|               x|
| Normal                  | scale                      |         0.05|          1.0|             1.0|
| Uniform                 | scale                      |         0.05|       [0, 1]|            None|

### Symbol Meanings
- x: No implementations
