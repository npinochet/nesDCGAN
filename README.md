# nesDCGAN
A DCGAN model to generate NES like game screens

## About
This is a project made for fun trying to generate textures for another project. The work made here is based on [this great article](https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7) by Adam Geitgey (@ageitgey). I used the oficial PyTorch DCGAN example as a base and used the CIFAR-10 pre trained parameters as a base to start training. These models where only tested running on Google Colab.

## Results
The output was cherry picked based on how good the result looked. This was generated using an Adam optimizer with a learninig rate of 0.002 and a batch size of 64. Other hyper-parameters can be found on the notebook.

### Input
![Input image](results/real_samples.png?raw=true "Input image")

### Output
![Output image](results/fake_samples_epoch_110.png?raw=true "Output image")

As you can see, results are mixed. It seems like there are some NES style tiles in there, but only if you look really hard for them, otherwise it looks really blurry.
