# Booster LEAP notebooks

Jupyter notebooks that go with the Booster LEAP courses. Each notebook opens in Google Colab from the lesson page; it needs no GPU unless it says so.

- `computer-vision/notebook-augmentation-e2e.ipynb`: does data augmentation help, and when?
- `computer-vision/notebook-cnn-from-scratch-e2e.ipynb`: a CNN from scratch, end to end
- `diffusion-models/notebook-environment-and-first-generation.ipynb`: environment check, memory arithmetic and a first tiny diffusion model on your machine (CPU or Colab GPU)
- `diffusion-models/notebook-train-tiny-ddpm.ipynb`: train a tiny DDPM end to end on 8 x 8 digits and on photo crops, sample with DDIM and DDPM, and measure the result
- `diffusion-models/notebook-latent-inference-e2e.ipynb`: a latent text-to-image pipeline end to end: a photo autoencoder, then a toy tokenizer, text encoder, autoencoder, U-Net, scheduler and guidance on digits, with measurements and a scheduler comparison
- `diffusion-models/notebook-cfg-sweep.ipynb`: a guidance-scale sweep on digits: a class-conditional model trained on a CPU, fidelity, diversity and out-of-range values per scale, three seeds, label dropout, editing strength and inpainting
- `diffusion-models/notebook-lora-e2e.ipynb`: LoRA end to end on a digit diffusion model: a base trained on the digits 0 to 6, a LoRA written by hand, ranks, merge scale, forgetting and replay with three seeds, and a few-patch photo denoiser adapted with full update against LoRA
