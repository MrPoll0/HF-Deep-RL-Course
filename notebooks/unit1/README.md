## Running locally
`conda create --name colab-env python=3.11`
`conda activate colab-env`
`conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia`
`conda install -c conda-forge gymnasium==0.28.1 stable-baselines3 "box2d-py>=2.3.5" pygame jupyterlab ipywidgets moviepy ffmpeg`
`pip install huggingface_sb3 sympy==1.13.1`
`jupyter lab`


