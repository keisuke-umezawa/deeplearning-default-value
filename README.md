# deeplearning-default-value

## Networks

| Function names in Chainer | Parameter names in Chainer | Chainer | PyTorch | TensorFlow | Keras |
|:------------------------- |:---------------------------|:-------:|:-------:|:----------:|:-----:|
| dropout                   | ratio                      |      0.5|      0.5|        None|   None|

## Initializers

| Function names in Chainer | Parameter names in Chainer | Chainer | PyTorch | TensorFlow | Keras |
|:------------------------- |:---------------------------|:-------:|:-------:|:----------:|:-----:|
| LecunNormal               | scale                      |      1.0|        x|           x|    1.0|
| Normal                    | scale                      |     0.05|      1.0|         1.0|   0.05|
| Uniform                   | scale                      |     0.05|   [0, 1]|        None|   0.05|

### Symbol Meanings
- x: No implementations
