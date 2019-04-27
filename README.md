# AI-Addin

Even if a machine learning model performs well, it is often crucial to understanding how an algorithm makes a certain decision. Trust in the model is enhanced when the logic is exposed. Machine learning models pick up biases from the training data, and exposing the internals of these models reveals their bias.

Model interpretability algorithms can reveal the logic and bias of these models, exposing the reasons in their predictions. Often the reasons for the predictions are as important as the predictions themselves. For example, accurately predicting someone's weight may not be as interesting as the reasons for the weight loss. The reasons provide the guidelines on how to change behavior. Understanding the reasons and logic can provide human-friendly explanations. Human-friendly explanations allow non-experts to understand complicated algorithms.

AIaddin(AI-addin) is artificial intelligence software that decides when and how to automatically apply model intrepretability algorithms to any data set that a user uploads for analysis, including: global surrogate models; word embeddings; individual conditional expectation (ICE) plots; k-local interpretable model-agnostic explanations (K-LIME); leave-one-covariance (LOCO); local feature importance; partial dependency plots; random forest feature importance; standardized coefficient importance; visualization of neural network layers; generalized low rank estimators; feature extraction and ranking; accumulated local effects (ALE) plots; and Shapley values.

We evaluate the system qualitatively, asking users if the human-friendly explanations are understandable and make logical sense given their domain expertise.
