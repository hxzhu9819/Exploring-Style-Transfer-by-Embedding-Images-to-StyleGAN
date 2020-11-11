# Exploring Style Transfer by Embedding Images to StyleGAN
This is the baseline model for 11-785 Project. This repo contains a functional VGG-StyleGAN architecture that can conduct style transfer.

* VGG: feature extractor
* StyleGAN2: syntheitic image generator



The baseline model is inspired by [Latent-Space-Exploration-with-StyleGAN2](https://amarsaini.github.io/Epoching-Blog/jupyter/2020/08/10/Latent-Space-Exploration-with-StyleGAN2.html) and forked from [here](https://github.com/boldwings/Epoching_StyleGan2_Setup). We've setup the code so as to allow the architecture to take user inputs.



Understanding how the feature extractor and StyleGAN2 generator are connected during forward and backward took most of our time. 



In the coming weeks, we will replace feature extractor with our customized network and validate our design and analysis.



Sources:

- [align_face.py](https://gist.github.com/lzhbrian/bde87ab23b499dd02ba4f588258f57d5)
- [stylegan2](https://github.com/NVlabs/stylegan2)
- [stylegan2directions](https://twitter.com/robertluxemburg/status/1207087801344372736)
