YAMNet experiments

This repository contains two notebooks with two different samples for YAMNet transfer learning: Wind and Sneeze

These are ran using Colab runtime version 2026.07 with T4 GPU

It is based on the transfer learning guide notebook provided by Google: https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/audio/transfer_learning_audio.ipynb with modifications such as:
- Dependencies are updated to support modern Python packages and runtime
- Updated my_classes list for expanded testing beyond dogs and cats classification
- Updated downloader and wav file loader logic to support custom uploaded wav sounds using upload button
