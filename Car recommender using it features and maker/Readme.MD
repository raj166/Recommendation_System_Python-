# Car recommendation system

This model uses the dataset from kaggle, the main aim of the notebook is to use NLP concepts to create a recommendation system

The model uses cosine similarity and eucildian distance to suggest few recommendation alternative to a car.

The recommendation is based on the look, type of car, type of gear box, Driven_Wheels ,Market Category and mostly all the features described in text or the dtype is Object.

It’s hard to visualize the word embedding directly, for they usually has more than 3 dimensions. T-SNE is an useful tool to visualize high-dimensional data by reducing dimensional space while keeping relative pairwise distance between points. The notebook uses genism for word2vec and tsne plot for some visualization of the data points.

The model provides 15 recommendation of a car based on the input car model.
