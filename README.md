# deeplearning-default-value
## Networks

| Functions     | Parameters                             | Chainer | PyTorch | TensorFlow | Keras |
|:------------- |:-------------------------------------- |:-------:|:-------:|:----------:|:-----:|
| dropout       | ratio: dropout ratio                   |      0.5|      0.5|        None|   None|

## Initializers

| Functions     | Parameters                             | Chainer | PyTorch | TensorFlow | Keras |
|:------------- |:-------------------------------------- |:-------:|:-------:|:----------:|:-----:|
| LecunNormal   | scale: scale of the standard deviation |      1.0|        x|           x|    1.0|
| Normal        | std: standard deviation                |     0.05|      1.0|         1.0|   0.05|
| Uniform       | scale: range of distribution           |     0.05|   [0, 1]|        None|   0.05|
