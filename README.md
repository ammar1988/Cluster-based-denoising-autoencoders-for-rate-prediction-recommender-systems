# Cluster-based-denoising-autoencoders-for-rate-prediction-recommender-systems


Cluster-based denoising autoencoders for rate prediction recommender systems

By Dr. Ammar Abdulsalam Al-Asadi, Email: ammar.alasadi26@gmail.com

This project proposed an optimized clustering-based denoising autoencoder model (OCB-DAE) which trains multiple models instead of one, based on users’ preferences using k-means algorithm combined with a nature-inspired algorithm (NIA) such as artificial fish swarm algorithm to determine the optimal initial centroids to cluster the users based on their similar preferences, and each cluster trains its own denoising autoencoder (DAE) model. The results proved that combining NIA with k-means gives better clustering results comparing with using k-means alone. OCB-DAE was trained and tested with MovieLens dataset where 80% of it is used for training and 20% for testing. Root mean squared error (RMSE) score was used to evaluate the performance of the proposed model.

# Source Paper
http://doi.org/10.11591/ijeecs.v30.i3.pp1805-1812

# Dataset
https://grouplens.org/datasets/movielens/100k/

# Github Reference
https://github.com/RaptorMai/Deep-AutoEncoder-Recommendation
https://github.com/guofei9987/scikit-opt
