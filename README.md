# Anomaly detection using autoencoder

This repository is a fork of the original [ADC2021 data challenge on anomaly detection at 40 MHz](https://mpp-hep.github.io/ADC2021/). This tutorial was modified to best suit the [US ATLAS Machine Learning Training Event 2022](https://indico.cern.ch/event/1169324/). Accompanying introducing anomaly detection can be found directly at the [link](https://indico.cern.ch/event/1169324/timetable/?view=standard#12-talk-with-hands-on-demo-ano)

This tutorial will cover:

1. Examples of model architectures using autoencoders for anomaly detection
2. How to train the model
3. Compute the model predictions on background data
4. Compute the model predictions on signal (anomalies)
5. Evaluate model's performance using 2 different techniques

# Autoencoder based on fully connected layers. Take a look at the file:

```bash
Dense_AE.ipynb
```

to follow along. Even though the architecture is pretty simple, we are still capable of finding all the anomalies with high background rejection! If you have time, change the basic model architecture and see if you can get an even better result!


# Autoencoder based on convolutional neural networks. Take a look at the file:

```bash
Convolutional_AE.ipynb
```
to follow along. In this example, images are created using different particles as the y-coordinate and their features as the x-axis. Even though the images we create are not the standard image one would expect, we still get a pretty model also capable of identifying all anomalies! Can you make that model even better?
