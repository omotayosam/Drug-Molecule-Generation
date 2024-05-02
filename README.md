# Drug-Molecule-Generation
intend to use Variational Autoencoder to generate molecules for drug discovery by integrating Variational Autoencoders (VAEs) for drug molecule generation with Large Language Models (LLMs) in the context of De Novo Drug Design.


#TODO
- combine the architecture that integrates both the VAE and the LLM. The VAE component will be responsible for generating molecular structures, while the LLM will handle natural language understanding and generation.

- Represent chemical compounds as molecular graphs or SMILES strings, which serve as input to both the VAE and the LLM.

- VAE Encoder and Decoder: Train the VAE encoder to map the input SMILES strings to a lower-dimensional latent space representation. Train the VAE decoder to reconstruct the input SMILES strings from samples in the latent space.

- LLM Integration: Use the LLM to process natural language input from users, such as descriptions of desired molecular properties or design criteria.
  





