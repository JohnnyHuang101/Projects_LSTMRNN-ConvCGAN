# Smaller_projects_LSTMRNN-convGAN

Two side projects I developed in a rather short amount of time. I have uploaded their code for my design, training, inspiration from papres, eval & testing procedures accordingly. Have a look!


The LSTM RNN project I implemented utilizes Keras, TF, Pytorch, and other powerful libraries for processing deeplearning audio-based signals to generate music. I framed the problem as such where we have the training data of the first segment of the music and we train the LSTM to try and generate the parts of the music that follows.

This method proved pretty effective in terms of simpler music types that are accoustic; I have the training errors across 1000s epochs to show.


LSTM/RNN
![image](https://github.com/user-attachments/assets/eee0e3aa-a30b-4da7-9532-1c04d23b2ebb)



I also created a project for utilizing convolutional Generative Adversarial networks for creating synthetic image datasets. This is my first attempt at creating a generative network for images but in the past I have worked with VAEs. I wanted to try out convolutional GANS particularily to see how well it would adapt to different modalities and the results were promising in terms of simplier images like MNIST. CelebA dataset was also attempted but GANS with the amount of layers I put was not strong enough and the errors remained high. I wonder if transformers can be tried next. I have the training log below.

Convolutional GAN
![image](https://github.com/user-attachments/assets/87a81b8a-e905-4b06-9d5d-233a21de3abb)
![image](https://github.com/user-attachments/assets/96b117a6-6218-4d8f-a491-d540131a330f)
