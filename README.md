# CycleGANProj
Converts real images to paintings in the style of the artist whose training data is used.
CycleGAN uses two generators and discriminators to play a game of cat and mouse where the generator tries to generate an image the discriminator cannot differentiate well. 
For Example, in this scenario one of the generators will try to generate the image of a painting such that the discriminator won't be able to tell very well if it's a real painting or not. 

The discriminator is trained directly on real images whereas the generator is not trained directly and instead is trained via the discriminator model.

The loss values corresponding the the Generators and Discriminators determine how well each one is at doing their job.
