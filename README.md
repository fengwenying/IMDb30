# IMDb30
IMDb30 is a film KG dataset, formed as triplet (h, r, t).

Paper: IMDb30: A Multi-relational Knowledge Graph Dataset of IMDb Movies

The code for constructing IMDb30 is in `imdb_movie_KG/imdb_movie_KG.ipynb`, the original triplets are stored in `imdb_movie_KG/IMDB30`, the divided dataset that can be used for model training and evaluating are stored in `imdb_movie_KG/IMDB_benchmark`.

The code for convolution model (ConvKB, ConvE, Conv3D) training and evaluating is in `model_4_imdb`.

The code for embedding visualization is in `visualization`.
