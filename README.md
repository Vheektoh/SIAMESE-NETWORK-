# SIAMESE NETWORK USED FOR SIMILARITY SEARCH OR FACIAL RECOGNITION SYSTEM
 A Siamese Network is a type of neural network architecture that is particularly useful for tasks involving similarity comparison.
 A Siamese Network consists of two identical sub-networks (often convolutional neural networks, CNNs) that share the same parameters and weights.
 These networks process two different input samples independently. Each sub-network extracts features from its respective input. Because the weights are shared, 
both inputs are transformed in the same way, ensuring consistent feature extraction. After feature extraction, a comparison layer (often a distance metric like 
Euclidean distance or cosine similarity) calculates the similarity between the two feature vectors produced by the twin networks. A common loss function used for 
training Siamese Networks is contrastive loss, which encourages the network to output similar feature vectors for similar inputs and dissimilar feature vectors 
for dissimilar inputs.
# APPLICATIONS
- Siamese Networks are used to verify if two face images belong to the same person.
- These networks can compare handwritten signatures to determine if they are from the same person.
- They are used in image retrieval systems to find images that are similar to a query image.
- In scenarios where the model needs to recognize classes with very few training examples, Siamese
  Networks can generalize better because they learn to measure similarity rather than classify directly. This is known as one shot learning.
