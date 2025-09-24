https://luma.com/gtxhcisu 
1. Inspired by this talk, simple exploration of the user embeddings with respect to the user demographics.
2. Movie lens 1M is one of the rare reco datasets that contain user meta like age, gender, occupation, zip code.
3. Analysed direct rating based, PMI (point wise mutual information) based and the collaborative filtering signals using ALS (alternating least squares).
4. Didn't try the deep learning based approaches like the two tower yet.
5. Will scrape more movie meta before giving it a shot.

## Installing the requirements
```
uv venv --python 3.12
uv pip install -r requirements.txt
```
## Running tensorboard
tensorboard --logdir tensorboard_embeddings/ 


## Insights v1:
Kids: Boys turned to Toy Story 2, Matrix, and Star Wars: Phantom Menace—a mix of Disney and sci-fi. Girls loved Toy Story, Aladdin, 101 Dalmatians, and The Parent Trap.

Younger Males: Star Wars, Matrix, Fight Club, and Terminator 2 ruled with action vibes.

Younger Females: American Beauty, Titanic, Shakespeare in Love, and Princess Bride captured romance and drama.

Adult Males: American Beauty, The Godfather, and Saving Private Ryan balanced drama and war epics, with Star Wars as a timeless anchor.

Adult Females: American Beauty, Casablanca, Schindler’s List, and Annie Hall highlighted classic dramas and romance.