# LLM-Prompt-Recovery

This will be my playground to explore how to recover the LLM prompt that was used to transform a given text.

#### Thursday, February 29, 2024

Today I entered the Kaggle LLM Prompt Recovery competition, and I want to have a local playground for this. 
I have created a new LLM-Prompt-Recovery repo for this. 

1) mamba create -n kllmpr python=3.11
2) mamba activate kllmpr
3) mamba install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
4) mamba install conda-forge::transformers
5) mamba install conda-forge::jupyterlab
6) mamba install conda-forge::ipywidgets
7) mamba install conda-forge::accelerate
8) mamba install conda-forge::bitsandbytes 

mamba activate kllmpr


