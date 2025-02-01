# ICEIC 2025
International Conference on Electronics, Information, and Communication (ICEIC) 2025
JAN. 19(SUN) – 22(WED), 2025 / Osaka International House, Japan

# ABSTRACT
This paper proposes a novel sound source localization method that combines Coherent-to-Diffuse Ratio (CDR) estimation with Generalized Cross-Correlation with Phase Transform (GCC-PHAT) to improve Time Difference of Arrival (TDOA) estimation in reverberant and noisy environments. First, a binary diffuseness mask derived from CDR estimation is applied to suppress the effects of reverberation and noise. Then, the GCC-PHAT algorithm is used to calculate the crosscorrelation between signals from two microphones, followed by a Convolutional Neural Network (CNN) structure adopted from the PGCC paper to refine the TDOA estimation. The proposed method demonstrates superior performance in complex acoustic environments compared to the conventional GCC-PHAT. Experimental results using simulated data show that, in a challenging environment with T60 of 0.6 seconds and a very low SNR of 0 dB, the Mean Absolute Error (MAE) decreased from 1.40 cm with the conventional GCC-PHAT method to 0.94 cm with the proposed method.

![image](https://github.com/user-attachments/assets/49b1d4fa-6c31-4681-9e5e-6d7227729d2c)
