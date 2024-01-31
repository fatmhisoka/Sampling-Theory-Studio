# Sampling Theory Studio

## Introduction
Sampling an analog signal is a crucial step for any digital signal processing system. The Nyquist–Shannon sampling theorem guarantees a full recovery of the signal when sampling with a frequency larger than or equal to the bandwidth of the signal (or double the maximum frequency in case of real signals).

## Description
Develop a desktop application that illustrates the signal sampling and recovery showing the importance and validation of the Nyquist rate. Your application should have the following features:

- **Sample & Recover:** Allow the user to load a mid-length signal (around 1000 points length), visualize and sample it via different frequencies, then use the sampled points to recover the original signal using Whittaker–Shannon interpolation formula. Sampling frequency should be shown in either actual frequency or normalized one (with respect to the maximum frequency, i.e. ranges from 0×fmax to 4×fmax for example). You should use three graphs, one for displaying the original signal along with the markers for the sampled points and another one to display the reconstructed signal, and lastly the third one should display the difference between the original signal and the reconstructed one.

- **Load & Compose:** The loaded signal can come from a file or a signal mixer/composer in your application. In the signal mixer, the user can add multiple sinusoidal signals of different frequencies and magnitudes. The user can also remove any of the components during preparing the mixed signal.

- **Additive noise:** The user can add noise to the loaded signal with custom/controllable SNR level.






