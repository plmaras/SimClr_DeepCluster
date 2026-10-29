# SimCLR and DeepCluster Experiments

SimClr : https://forge.coreweave.com/wandb/shriramgolla-iit-hyderabad/simclr-cifar10-ablations_3/

Deep Cluster : https://forge.coreweave.com/wandb/shriramgolla-iit-hyderabad/deepcluster-cifar10/

This project explores self-supervised learning techniques for learning visual representations from unlabeled images.

### SimCLR Experiments
- Train a CNN to learn image representations using contrastive learning.
- Generate multiple augmented views of each image and learn to identify positive pairs.
- Experiment with different image augmentations and model configurations.
- Analyze learned representations and evaluate their quality using downstream classification.

### DeepCluster Experiments
- Extract feature representations from images using a CNN.
- Cluster the extracted features using K-means to generate pseudo-labels.
- Train the network to predict cluster assignments.
- Iteratively update clusters and refine the learned representations.

### Goal
Compare contrastive learning and clustering-based self-supervised learning to understand their effectiveness in learning meaningful visual features without manually annotated labels.