# Interactive-AI-Designer
An interactive system that can genrate artworks based on user's requirement(both content and style)
.<br>
A combination of GAN trained on wikiart along with MS COCO and neural style transfer<br>
The neural style transfer is based on the code from [this](https://github.com/anishathalye/neural-style)<br>
The GAN is based on [this](https://github.com/carpedm20/DCGAN-tensorflow) implementation, and updated to WGAN with graient penalty and matching aware critic that can do text-to-image generation<br>

# Our latest system
![image](https://github.com/icarusization/Interactive-AI-Designer/blob/master/GUI.jpg)

# To do
1. Generate high-quality images with higher resolution(256*256)
2. Integrate arbitray style transfer(arXiv:1703.06868)


