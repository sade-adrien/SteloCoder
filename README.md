# SteloCoder

SteloCoder is a model designed for code machine translation from multiple languages (C++, C#, Java, JavaScript, PHP) to Python. It is based on StarCoder to which we have added additional parameters using LoRA and MoE methods.

For technical description please refer to our paper: 
https://arxiv.org/abs/2310.15539

How to use:
- Our implementation is based on the transformers library. You need this package installed.
- Replace the modeling_gpt_bigcode.py file by ours in /transformers/models/gpt_bigcode
- Refer to starter.ipynb for a starter code
