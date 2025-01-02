# Utilizing a Deep Learning Pipeline to Generate Antigen-Conditioned Nanobodies

*Note: the full project (code and manuscript) is in a private repo, reach out to matthewsalfity@gmail.com for more information*

In this project, we successfully trained a nanoGPT model and used the trained model to generate de novo nanobody sequences, then used a pre-made nanoBERT model to train a nanobody classifier multilayer perceptron (MLP). The classifier was benchmarked against an equivalent ESM-2 classifier and a one-hot encoded classifier, with the nanoBERT and ESM-2 classifiers outperforming the one-hot encoded classifier. We then evaluated the 1,000 generated nanoGPT sequences using the trained classifier, finding that nearly all were identified as nanobodies. Finally we trained a CLIP model, as well as ESMfold, to evaluate our library of de novo nanobodies linked to the antigen, a malarial protein from the parasite Plasmodium falciparum, and found that . Overall, we showed the potential for PLMs to generate realistic de novo nanobodies and potential of CLIP to act as a screening mechanisms for nanobody targets.
