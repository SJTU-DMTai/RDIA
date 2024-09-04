This repository is the official implementation of our ICLR2022 paper: "[Resolving Training Biases via Influence-based Data Relabeling](https://openreview.net/forum?id=EskfH0bwNVn)".
RDIA aims to reuse harmful training samples toward better model performance. To achieve
this, we use influence functions to estimate how relabeling a training sample would
affect model’s test performance and further develop a novel relabeling function R to update the labels of identified harmful samples.
