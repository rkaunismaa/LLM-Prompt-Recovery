# LLM-Prompt-Recovery

This will be my playground to explore how to recover the LLM prompt that was used to transform a given text.

mamba activate kllmpr

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

#### Friday, March 1, 2024

Continue digging into the workings of gemma.

#### Thursday, March 7, 2024

Keep at it ... 

#### Saturday, March 16, 2024

Attempting to run the Kaggle notebook [Prompt Recovery with Gemma - KerasNLP Starter](https://www.kaggle.com/code/awsaf49/prompt-recovery-with-gemma-kerasnlp-starter) locally ... This notebook use Keras and Jax, so yeah, gonna I need to install those libraries. 

Hmmm just to be safe, I am going to clone the kllmpr environment to kllmpr-2 and run the installs in that environment. 

 #### Sunday, March 17, 2024

 So I didn't clone the environment yesterday, but will do it now and continue ... working through the notebook 'Local_prompt-recovery-with-gemma-kerasnlp-starter.ipynb'

  1) mamba create --name kllmpr-2 --clone kllmpr
  2) mamba activate kllmpr-2
  3) mamba install conda-forge::keras
  4) pip install --upgrade "jax[cuda11_pip]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
  5) pip install --upgrade keras-cv
  6) pip install --upgrade keras-nlp
  7) pip install --upgrade keras
  8) mamba remove conda-forge::keras  ... cuz keras was broken ... 
  9) pip install --upgrade keras
 10) mamba install conda-forge::plotly





