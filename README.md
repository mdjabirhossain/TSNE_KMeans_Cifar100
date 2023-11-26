# TSNE_KMeans_Cifar100

The idea is to explore an image dataset, named cifar100. It has 60_000 colorful images. Thus, looking at each of them is not feasible. We are applying tSNE and kMeans and look at nearest neighbours (in the Euclidean metric). We will examine how TSNE and KMeans perform in clustering these images into meaningful groups.

The goal is to:

- Observe what patterns are picked up in the images, and understand why that happens.
- Try to understand limitations of using the Euclidean distance to capture the dissimilarity between images.

The code mostly work with (high-dimensional) vectors, norms, distances, sums, and means.

There are be 4 major parts:

- Loading data, checking format etc.
- Preparing a function for finding nearest neighbours.
- Exploratory data analysis with tSNE (and nearest neighbours)
- Clustering with kMeans (informed by the above part)
