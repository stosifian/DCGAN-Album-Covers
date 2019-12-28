# Final Project
## Network Judging Other Network's Album Art

Shawheen Tosifian, stosifia@ucsd.edu

## Abstract Proposal

This project is an extension of the Generative Visual project (for ECE 188 at UCSD) where a GAN was trained on 64x64 images of album covers and reproduced it's own 'album art'. This project extends on the concept by having an emotion 'classifer' network based off the pretrained VGG16 model trained on a small abstract art dataset assign an emotion to a piece of GAN 'album art'. The primary motivation behind is to see if album art is emotive (at least through a quantitative approach) and if it matches the album's desired response through its music as well as to see if a neural network can try to classify the 'emotion' that another neural network might have produced with its art. This can be extended to much greater depths but that'd be somewhat foolish to do for a GAN trained on 64x64 album artwork and a classifier on an even smaller dataset of abstract art...


## Project Report

Inside repo (ECE188_Final_Project_Report)

## Model/Data
- abstract_64x64 : directory containing images of abstract art resized to 64x64 (with corresponding .csv containing
                   each images sentiment labels) obtained from https://www.imageemotion.org
- abstractclass1 : checkpoints for classifier (not available due to git push issue - available upon request)
- dcgan_results : sample output of DCGAN over every iteration (not available due to git push issue - available upon request)
- GANAlbumArt : contains generated DCGAN 'album art' files (not available due to git push issue - available upon request)
- AbstractClassifier: .ipynb notebook for classifier
- DCGAN_AlbumArt: .ipynb notebook for DCGAN
- nntools.py: used by AbstractClassifier for importing classes/functions needed to run model
- README.md: where you are now

## Code
- Python: nntools.py <- needed to run AbstractClassifier.ipynb
- Jupyter notebooks: DCGAN_AlbumArt.ipynb <- train and generate 64x64 'album art'
                     AbstractClassifier.ipynb <- classifies 'album art' with emotion

## Results
-> In AbstractClassifier.ipynb for now


## Reference

References to any papers, techniques, repositories you used:
https://www.imageemotion.org
