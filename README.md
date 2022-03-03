# Classification-Loss-Comparison
Densenet121 models is compared with Triple loss, Center loss and Cross-entropy loss models. Cross-Entropy Loss Function. Also called logarithmic loss, log loss or logistic loss. Each predicted class probability is compared to the actual class desired output 0 or 1 and a score/loss is calculated that penalizes the probability based on how far it is from the actual expected value. Triplet loss is a loss function for machine learning algorithms where a reference input (called anchor) is compared to a matching input (called positive) and a non-matching input (called negative). Center loss reduces the distance of each data point to its class center. It is not as difficult to train as triplet loss and performance is not based on the selection process of the training data points(triplets). Combining it with a softmax loss, prevents embeddings from collapsing.

## Model: Densenet121
## Dataset: Tiny Imagenet
Tiny imagenet is a dataset of 200 classes. Training set contains 500 image in each class, a total of 1 lakh images.
