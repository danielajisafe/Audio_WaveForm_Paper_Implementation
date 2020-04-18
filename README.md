This is an implementation of the paper "Very deep convolutional neural networks for raw waveforms" by Wei Dai*, Chia Dai*, Shuhui Qu, Juncheng Li, Samarjit Das. The paper is found [here](https://arxiv.org/pdf/1610.00087.pdf) and was implemented in Pytorch.

### Requirements:
To get started, Torchaudio, Pytorch, Numpy and Pandas needs to be installed.

Instructions on how to carry out these installations are found below:
[Pytorch](https://pytorch.org/),
[Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html),
[Numpy](https://pypi.org/project/numpy/),
[torchaudio](https://github.com/pytorch/audio)

The dataset used for the implementation of this project is found [here](https://urbansounddataset.weebly.com/urbansound8k.html).

### Challenges:
Google Colab session expires after 12 hours at the longest. We also discovered the final architecture (M34 which includes residual blocks) took the longest time. For this reason, we ran the script on two seperate instances. The first instance from M3 to M34 and the other one from M34 to M3 (reversely). Store the loss and accuracy information for each fold and stop training when they meet somewhere at the middle. Our parallelized approach reduced training time significantly.

#### Collaborators:
Daniel Ajisafe, Oluwabukola Grace Adegboro, Carole Fosso and Hussam Eldeen Mohamed.

 
