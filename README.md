- [X] Step 1: Initialization

- Load the weights
- Write the architecture in JAX
- Run inference

- [ ] Step 2: Data Generation

- Select a layer to be inspected
- Read [this](https://transformer-circuits.pub/2023/monosemantic-features#appendix-autoencoder-dataset) portion to generate data 
     - Select text, run inference
     - Save a particular layer's activation vectors
- Save the activation vectors to be the dataset

- [ ] Step 3: Training SAE

- Using the generated dataset, train a simple SAE
- Use various tips ans tricks applied in the [paper](https://transformer-circuits.pub/2023/monosemantic-features#appendix-autoencoder)
- Apply visualisation
- Use automated interpretability for the final step

- [ ] Bonus 

See if [sampling](https://github.com/xjdr-alt/entropix/blob/main/entropix.ipynb) can be done at an earlier layer, and choose which layer to do it on based on the interpretation and the user intention. (Use the [spectrum](https://arxiv.org/pdf/2406.06623) technique to find importance (based on a prompt ??)).