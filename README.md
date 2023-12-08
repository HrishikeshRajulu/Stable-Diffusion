# PyTorch Implementation of Stable Diffusion v1.5

This guide outlines the steps to implement the Stable Diffusion v1.5 model using PyTorch. Follow these instructions to set up and use the model for generating AI-powered images.

## Prerequisites

Ensure you have Python and PyTorch installed on your system.

## Setup Instructions

### Clone Repository
Start by cloning this repository to your local machine.

### Download Tokenizer Files
Obtain `vocab.json` and `merges.txt` from the official [Stable Diffusion Tokenizer](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer).
Place these files in the `data` directory of the cloned repository.

### Download Model Checkpoint
Download `v1-5-pruned-emaonly.ckpt` from [Stable Diffusion v1.5](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main).
Save this checkpoint file in the `data` folder.

## Using Fine-Tuned Models
If you wish to use fine-tuned versions of the Stable Diffusion model (up to version 1.5), follow these steps:

- Download the `.ckpt` file from the desired fine-tuned model version. Example models include:
  - [InkPunk Diffusion](https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main)
  - [Illustration Diffusion (Hollie Mengert)](https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main)
- Replace the original `v1-5-pruned-emaonly.ckpt` in the `data` folder with the downloaded fine-tuned model checkpoint.

## Usage
After completing the setup, you can start using the model for image generation. Refer to the provided example scripts to understand how to utilize the model in your projects.
