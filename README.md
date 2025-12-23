# Deep JSCC implementation (AWGN) — CIFAR10

+ Minimal PyTorch implementation of Deep Joint Source-Channel Coding (DeepJSCC) over an AWGN channel.
+ Trains separate models at fixed SNR_train ∈ {1,4,7,13,19} and evaluates PSNR across SNR_test sweep.

+ This implements training of Deep JSCC models for wireless image transmission as described in the paper Deep Joint Source-Channel Coding for Wireless Image Transmission by Pytorch. And there has been a Tensorflow and keras implementations .

## Result
![AWGN PSNR](results/plots/awgn_psnr.png)
