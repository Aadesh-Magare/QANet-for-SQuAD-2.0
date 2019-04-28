# BiDAF Baseline model for SQuAD 2.0

## Introduction

Implementation of BiDAF model for SQuAD 2.0 dataset.

## Usage

Setup environment and preprocess data:

conda env create -f environment.yml

conda activate squad

python setup.py

Start training model:

python train.py -n baseline

## Structure

 args.py: Command-line arguments for setup.py, train.py, and test.py

 environment.yml: List of packages in the conda virtual environment

 layers.py: Layers used by the models

 models.py: The starter model, and any others you might add

 setup.py: Downloads pretrained GloVe vectors and preprocesses the data

 train.py: Top-level entrypoint for training the model

 test.py: Top-level entrypoint for testing the model and generating submissions for the leaderboard

 util.py: Utility functions and classes

## Acknowledgement
1. Model is taken from https://github.com/chrischute/squad
