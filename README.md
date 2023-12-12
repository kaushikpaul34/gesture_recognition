# Gesture Recognition
> Train a deep learning model to identify various gestures for smart TV.


## General Information
- Develop an advanced smart TV feature utilizing the built-in webcam for continuous gesture monitoring. Users can control the TV through five distinct gestures:
1) Thumbs up: Increases the volume.
2) Thumbs down: Decreases the volume.
3) Left swipe: Jumps backward 10 seconds in the content.
4) Right swipe: Jumps forward 10 seconds in the content.
5) Stop gesture: Pauses the current movie or TV show.
- The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images).
- The ultimate goal is to deploy a well-trained model that can seamlessly integrate with the smart TV system, accurately interpreting user gestures and enabling a responsive and intuitive control mechanism.


## Conclusions
- Experimentation has been undertaken, encompassing a spectrum of Conv3D and Conv2D+LSTM models, each configured with diverse batch sizes and input shapes.
- The model that demonstrated the highest efficacy is identified as the Conv2D+LSTM architecture. 
- The implementation incorporates transfer learning from MobileNet, has yielded a validation accuracy of 93.5%, underscoring its proficiency in accurately discerning and classifying user gestures.

## Contact
Created by [@kaushikpaul34] - feel free to contact me!
https://www.linkedin.com/in/kaushik-paul-a31384169
