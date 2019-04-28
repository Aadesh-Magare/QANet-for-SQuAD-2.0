# QANet for SQuAD 2.0

## Introduction

Implementation of [QANet](https://arxiv.org/pdf/1804.09541.pdf) for SQuAD 2.0 dataset.

## Usage

Run `python3 QANet_main.py --batch_size 32 --epochs 30 --with_cuda --use_ema ` to train model with cuda.

Run `python3 QANet_main.py --batch_size 32 --epochs 3 --with_cuda --use_ema --debug` to debug with small batches data.

## Structure
QANet_main.py: driver program

trainer/QANet_trainer.py: trainer.

model/QANet_model.py: defines QANet.

data_loader/SQuAD.py: SQuAD 1.1 and 2.0 data loader.

## Acknowledgement
1. The QANet structure implementation is mainly based on https://github.com/BangLiu/QANet-PyTorch
2. Baseline model is taken from https://github.com/chrischute/squad
