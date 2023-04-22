# EEG-Signal-Denoising-with-IIR-and-FIR-filters-with-MATLAB

Submitted to Dr. Gerald Arada as our final project in SIGDISC.
- Peruel, Ong, Laca, Dee

Abstract— The contamination of EEG signals with noise resulted in the loss of 
significant information such as signal trends or spikes. This study examined the impact 
of adding Gaussian noise to an EEG signal and the resulting loss of information. The 
EEG signal's power spectrum was analyzed to identify areas of higher power and a 
filter design was proposed to recover the original signal while attenuating noise across 
the stopband. Results showed that the normally-distributed noise added by the awgn() 
MATLAB function resulted in a uniform power distribution across all frequencies. The 
proposed filter design aims to match the power of the original EEG signal in the 
passband and attenuate noise across the stopband. The findings highlighted the 
importance of effective noise reduction techniques in EEG signal processing to 
preserve critical information. The SNR improvement, MSE, and RMSE values were 
used to assess the similarity of the recovered signals to the original EEG signal. All 
filters were effective in noise reduction, with the Chebyshev Type I filter being the best 
and the Chebyshev Type II filter being the worst in terms of SNR improvement. The 
Chebyshev Type II filter-recovered signal was the most similar to the original EEG 
data, while the Chebyshev Type I filter output was the least similar. The IIR filters 
produced the best SNR improvement, MSE, and RMSE, but the FIR filters also 
performed well in noise reduction and similarity.

EEG data:
I. Zyma, I. Seleznov, A. Popov, M. Chernykh, and O. Shpenkov, “EEG during mental arithmetic tasks,” EEG During Mental Arithmetic Tasks v1.0.0, 17-Dec-2018. [Online]. Available: https://physionet.org/content/eegmat/1.0.0/. [Accessed: 22-Apr-2023]. 
