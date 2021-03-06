<h1>Generative Adversarial Network</h1>
One neural network, called the generator, generates new data instances, while the other, the discriminator, evaluates them for authenticity; i.e. the discriminator decides whether each instance of data that it reviews belongs to the actual training dataset or not.
Meanwhile, the generator is creating new, synthetic images that it passes to the discriminator. It does so in the hopes that they, too, will be deemed authentic, even though they are fake. The goal of the generator is to generate passable hand-written digits: to lie without being caught. The goal of the discriminator is to identify images coming from the generator as fake.

<h1>Fake Image Generator using Deep Convolutional Generative Adversarial Network</h1>
Here are the steps a GAN takes:

:> The generator takes in random numbers and returns an image.<br>
:> This generated image is fed into the discriminator alongside a stream of images taken from the actual, ground-truth dataset.<br>
:> The discriminator takes in both real and fake images and returns probabilities, a number between 0 and 1, with 1 representing a prediction of authenticity and 0    representing fake.

<h1>Real Images</h1>
<center><img src="/Images/real_samples.png"></center>
<h1>After Generated Fake Images using GAN</h1>
<center><img src="/Images/fake_samples_epoch_002.png"></center>
