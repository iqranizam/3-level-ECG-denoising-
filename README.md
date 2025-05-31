# 3-level-ECG-denoising

We used 3 level ECG denoising technique to remove the additional noises. Butterworth low pass filter is used to remove the signal with frequency above 50 Hz, LOESS curve fitting is utilized to get rid of baseline wandering, and Non Local Means (NLM) handles the left noises. 
