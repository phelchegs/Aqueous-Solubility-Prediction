# machine-learning-project-4
Aqueous solubility prediction
It is difficult to decide which solvent to use for organic reactions, especially for aqueous media, which is advantageous in terms of green chemistry, in our daily chemistry research and production. The main concern is to deciding how much compounds will dissolve into water media to process the reaction as the homogenious state. Herein, several machine learning models trained by the AqSolDB dataset, which contains 9k to 10k observations with Log10S solubilities and other chemical descriptors, such as molecular weights, number of rings, and topological properties, are built up with hypertuning. The non-linear models or with non-linear kernels showed good accuracy on testing set. Models also showed the importance of features. It seems like LogS is mainly determined by LogP (octanol-water partition coefficient), molecular weight, and the topological feature, BertzCT. The well-trained models are expected to play important roles in predicting LogS for compounds out of this dataset and direct the use of water as reaction media in the future.
