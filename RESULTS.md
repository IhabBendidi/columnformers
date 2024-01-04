# Results

## ImageNet-100

Columnformer performance trained on [ImageNet-100](https://huggingface.co/datasets/clane9/imagenet-100) at 128x128 resolution for 100 epochs.

| description | commit | # of params | Depth  |  geometry | accuracy |
|------------|--------|-------------|-----------|----------|----------|
| baseline | [690dd2c](https://github.com/IhabBendidi/columnformers/tree/690dd2c733f1fa029e43e87cf5ce99a5c3b90608)| 47M | 6 | [8, 12, 16]  |      22.8%       |
| Depth |   [f560433](https://github.com/IhabBendidi/columnformers/tree/f5604333e57cc36750717cefd9dd1bc24357d3ca) | 47M | 9 | [8, 12, 16]  |      12.8%       |
| Depth |   [f67cb53](https://github.com/IhabBendidi/columnformers/tree/f67cb53e9f87dcd632ca6827fb6723c8328d56ea) | 47M | 3 | [8, 12, 16]  |      30.0%       |
| Depth |   [6ae54a4](https://github.com/IhabBendidi/columnformers/tree/6ae54a4c76ae8242f513571e5437f452cb885534) | 47M | 2 | [8, 12, 16]  |      29.7%       |
| Depth |   [98db8d3](https://github.com/IhabBendidi/columnformers/tree/98db8d30bd3e3b2231351668a12678200cfa3a15) | 47M | 1 | [8, 12, 16]  |      30.4% (34% at 200 epochs)       |
