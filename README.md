## Modifications
This is a fork of [gReLU](https://github.com/Genentech/gReLU) with the following modifications:

- Modified the Crop layer's forward function to handle sequences with length > 896 by keeping the middle 896 positions and cropping equally from both ends.

## Installation
You can install this modified version directly from GitHub:
```bash
pip install git+https://github.com/yangzhao1230/gReLU.git@feature/custom-crop