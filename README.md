# Audio_WaveForm_Paper_Implementation

This is an implementaion of the paper "Very deep convolutional neural networks for raw waveforms" by Wei Dai*, Chia Dai*, Shuhui Qu, Juncheng Li, Samarjit Das. Paper here --> https://arxiv.org/pdf/1610.00087.pdf and was implemented in Pytorch.

Challenges: Google Colab session expires after 12 hours at the longest. We also discovered the final architecture (M34 which includes residual blocks)  took the longest time. For this reason, we ran the script on two seperate instances. The 1st instance from M3 to M34 and the other one from M34 to M3 (reversely). Store the loss and accuracy information for each fold and stop training when they meet somewhere at the middle. Our parallelized approach reduced training time significantly.


Collaborators:
Daniel Ajisafe, Grace Adegboro Oluwabukola, Carole Fosso and Hussam Eldeen Mohamed


 
