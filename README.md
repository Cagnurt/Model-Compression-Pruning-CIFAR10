# Model-Compression-Pruning-CIFAR10

This repository focuses on compressing a pretrained model on the CIFAR10 dataset to reduce model size and/or improve CPU inference time. The chosen compression method is Pruning, implemented using PyTorch's pruning functionality.

The notebook, `Pruning.ipython`, provides a detailed and self-explanatory guide to the experiment. It showcases the application of L1 pruning in both unstructured and structured ways, with varying amounts/proportion rates of pruning. The notebook is organized in a clear manner, ensuring easy comprehension.

By exploring the notebook, you can examine the experiment's results and evaluate the impact of different hyperparameters, namely structuring/not structuring and the amount/proportion rate of pruning, on model compression. Witness how pruning affects the model size and CPU inference time, gaining insights into efficient model compression techniques.

Join this repository to gain hands-on experience in compressing pretrained models on CIFAR10 using pruning methods and uncover the potential benefits of reducing model size and enhancing CPU inference time.