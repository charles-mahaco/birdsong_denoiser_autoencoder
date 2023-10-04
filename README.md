# Birdsong Denoiser

This is a "toy" denoiser specifically made for cleaning birdsongs as part of my final project for the Python for Artificial Intelligence training I took at DigitalCity Brussels.

It works using a basic autoencoder architecture trained on clean target birdsongs from Xeno-Canto with noisy input made from the same birdsongs mixed with noise from the FSC-22 and ESC-50 datasets. I also used non-stationary noise reduction with the "noisereduce" library to clean further my predictions.


## Results

Waveform comparison:

![waveform_compare](https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/blob/main/waveform_compare.png)

Spectrogram comparison:

![spectrogram_compare](https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/blob/main/autoencoder_pred_spec.png)

## Soundfiles

Test on a birdsong with crowd noise:


https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/assets/43580564/4bc897c6-25e5-49e8-a38f-53060f6f46a4

Denoised (AE + Spectral Gating)


https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/assets/43580564/f160fd19-d9fb-4f5a-b49a-016a7b4454fd

Extreme test on a birdsong with lions, clapping, fireworks, coughing & more:

https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/assets/43580564/2a102562-5ffb-4ea1-a5f7-40e75007f524

Denoised (AE + Spectral Gating)


https://github.com/charles-mahaco/birdsong_denoiser_autoencoder/assets/43580564/3d4f17f3-35ab-48d2-9816-60e34bb6f1e3





