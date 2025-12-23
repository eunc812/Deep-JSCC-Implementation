# Deep JSCC implementation 

+ Minimal PyTorch implementation of Deep Joint Source-Channel Coding (DeepJSCC) over an AWGN channel.
+ Trains separate models at fixed SNR_train ∈ {1,4,7,13,19} and evaluates PSNR across SNR_test sweep.
+ This implementation is based on the paper [Deep Joint Source-Channel Coding for Wireless Image Transmission](https://ieeexplore.ieee.org/abstract/document/8723589).

+ [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/drive/16rcHuqdTN3X9q8ojp25UNF-BZUXzhOqT?usp=sharing
)


## train
python train.py 

## evaluation
python eval.py

## Result
![AWGN PSNR](results/awgn_psnr.png)
