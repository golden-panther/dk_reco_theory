https://luma.com/gtxhcisu 
1. Inspired by this talk, simple exploration of the user embeddings with respect to the user demographics.
2. Movie lens 1M is one of the rare reco datasets that contain user meta like age, gender, occupation, zip code.
3. Used the collaborative filtering signals.
4. Didn't try the deep learning based approaches like the two tower yet.
5. Will scrape more movie meta before giving it a shot.

## Installing the requirements
```
uv venv --python 3.12
uv pip install -r requirements.txt
```
## Running tensorboard
tensorboard --logdir tensorboard_embeddings/ 