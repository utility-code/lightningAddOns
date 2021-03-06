# Lightning AddOns

- Additional functionality for [Pytorch Lightning](https://github.com/PyTorchLightning/pytorch-lightning)

# Pip!!
- Now you can directly do a pip install
- pip install lightningaddon

# Useful functions
- Please check [DOCUMENTATION](https://subhadityamukherjee.github.io/lightningAddOns/)
- For some useful functions check [use](useful.md)

## Features (in progress)
- The documentation is in progress and of course, many more features are on the way. 
### General
- compose multiple functions on data
- time any function
- parallelly run any function on a list
- download from url

### Torch related
- model vis using hiddenlayer
- clear gpu memory easily 
- flatten
- get a histogram
- find modules with a condition
- check if linear layer
- seed everything
- freeze/unfreeze parts of a model
- count paramemeters and display tables
- count paramemeter state (frozen/unfrozen)
- easy pil<->tensor
- open image -> resize -> convert to tensor

## Models
- xresnet (all variants)

## Requirements
- PyTorchLightning. (This will install pretty much everything else)
- einops

## FAQ
- Why?
        - Well, lightning is an awesome library but there are some things I wanted globally so I decided to make an "Add Ons" package. 
- Why not contribute instead?
        - I might once this package does significant extra stuff

## Thank you
- A huge thank you to Jeremy Howard and [fastai](https://github.com/fastai). Many of these tricks are inspired by the amazing work done there. 
