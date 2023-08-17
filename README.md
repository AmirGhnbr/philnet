# PhilNet

This is a TensorFlow 2 implementation of the [PhilNet paper](https://www.sciencedirect.com/science/article/pii/S0020025523003183)

## Requirements

- Python 3.6 or later
- TensorFlow 2.0 or later

## Summary

- PHILNet is a novel approach for time series forecasting using deep learning.

- PHILNet separates the model into levels, starting with the easiest and continuing to the most difficult. The simpler levels deal with smoothed versions of the input, whereas the most sophisticated level deals with the raw data. This strategy seeks to mimic the human learning process, in which basic tasks are completed initially, followed by more precise and sophisticated ones.

- PHILNet achieved promising results, obtaining a 35% improvement in mean squared error and a 2.6 time decrease in training time compared with the best models found in a variety of time series

## Architecture

![Philnet Architecture](https://github.com/AmirGhnbr/philnet/blob/main/assets/philnet.PNG?raw=true)
