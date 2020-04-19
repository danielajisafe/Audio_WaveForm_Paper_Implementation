This is an implementation of the paper "Very deep convolutional neural networks for raw waveforms" by Wei Dai*, Chia Dai*, Shuhui Qu, Juncheng Li, Samarjit Das. The paper is found [here](https://arxiv.org/pdf/1610.00087.pdf) and was implemented in Pytorch.

### Requirements:
To get started, Torchaudio, Pytorch, Numpy and Pandas need to be installed.

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

 

On Sat, 18 Apr 2020 at 22:02, Grace Oluwabukola Adegboro <gadegboro@aimsammi.org> wrote:
hi# Audio_WaveForm_Paper_Implementation

This is an implementaion of the paper "Very deep convolutional neural networks for raw waveforms" by Wei Dai*, Chia Dai*, Shuhui Qu, Juncheng Li, Samarjit Das. The paper is found [here](https://arxiv.org/pdf/1610.00087.pdf) and was implemented in Pytorch.

### Requirements:
To get started, pytorch, pandas, numpy and torchaudio needs to be installed or imported.

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

-- 
Oluwabukola Grace AdegboroAfrican Masters in Machine Intelligence | QLAMob. +2348162338948 | Tel. +250787450334Email: gadegboro@aimsammi.orgSkype id: oluwabukola.adegboro
DISCLAIMER: The contents of this email and any attachments are confidential. They are intended for the named recipient(s) only. If you have received this email by mistake, please notify the sender immediately and you are herewith notified that the contents are legally privileged and that you do not have permission to disclose the contents to anyone, make copies thereof, retain or distribute or act upon it by any means, electronically, digitally or in print. The views expressed in this communication may be of a personal nature and not be representative of AIMS-NEI and/or any of its Centres or Initiatives.

-- 
Daniel AjisafeAfrican Masters in Machine Intelligence | AMMIMob. +250781603040 | Tel. +2348103574243Email: dajisafe@aimsammi.orgSkype id: ajisafedaniel
