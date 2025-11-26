# IE643 Project — Style Transfer & Generative Models

This repository contains experiments and notebooks for a course project (IE643) exploring neural style transfer, generative models, and related image synthesis techniques. The main artifacts are Jupyter notebooks that implement and compare different style transfer methods, generative approaches (VAE, StyleGAN), and related experiments (ControlNet, CLIP, ViT, etc.).


## Quick overview
- Primary focus: neural style transfer (NST), AdaIN, attention-based NST, and experiments with generative models and model variants.
- Main outputs: interactive Jupyter notebooks, model experiments and visual results saved within notebooks.
- How to use: open the notebooks in Jupyter / Colab; follow top cells for setup and dependencies.

## Repository contents (notebooks)
- Adain.ipynb
  - Implementation / experiments with Adaptive Instance Normalization (AdaIN) style transfer.
- Attenti+NST.ipynb
  - Attention-based neural style transfer experiments (likely with attention modules).
- Attention+NST+ADAIN.ipynb
  - Combined experiments mixing attention mechanisms and AdaIN style transfer.
- ControlNet+CLIP.ipynb
  - Experiments using ControlNet together with CLIP guidance for image generation or conditioning.
- ControlNet+IPAdapter.ipynb
  - ControlNet experiments using IPAdapter (an adapter/conditioning mechanism).
- FINALOSASIS.ipynb
  - Final Osasis-related experiment (likely the culminating experiment/version).
- NST.ipynb
  - Classic neural style transfer experiments (Gatys et al. style).
- Original_Osasis_from_paper.ipynb
  - Reproduction or study of the Osasis method from its paper (original implementation/analysis).
- PlainSTYLEGAN.ipynb
  - Experiments with a plain StyleGAN model (training or inference examples).
- VAE.ipynb
  - Variational Autoencoder experiments or demos.
- Zstar.ipynb
  - Experiments related to latent space manipulation (Z* or z-star ideas).
- final_model.ipynb
  - Consolidated final model experiment and results.
- final_model_metrix.ipynb
  - Metrics, evaluation, and visualizations for the final model(s).
- vit.ipynb
  - Experiments involving Vision Transformer (ViT) components or embeddings.


## How to run
1. Clone the repository:
   git clone https://github.com/LoPA607/IE643_project.git
   cd IE643_project

2. Open the notebooks:
   - Recommended: use JupyterLab, Jupyter Notebook, or Google Colab.
   - Example:
     jupyter lab
     then open any .ipynb file in the browser.

3. Install dependencies:
   - Many notebooks use PyTorch, torchvision, and common image libraries. Typical requirements:
     pip install torch torchvision matplotlib pillow numpy tqdm

4. For GPU/large experiments:
   - Use a GPU-enabled environment (Colab, local CUDA machine).


