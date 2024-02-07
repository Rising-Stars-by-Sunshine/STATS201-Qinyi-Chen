This data is downloaded from an open database which is the “Derivation and Validation of Heart Rate Variability Based Scoring Models for Continuous Risk Stratification in Patients with Suspected Sepsis in the Emergency Department by Machine Learning Algorithms”(Chen, 2020). This database includes a wide range of HRV-related features, nonlinear dynamics measures, and other statistical parameters that could be useful for analyzing heart rate variability. The data contains “Mean.rate”, the original source of mean heart rate; “Coefficient.of.variation”, the data of Heart Rate Variability; “LF.HF.ratio.LombScargle”, LF (Low Frequency) to HF (High Frequency) ratio calculated using Lomb-Scargle power spectral analysis, often related to autonomic nervous system activity.
This dataset can help us understand the raw data of HRV and its detailed characteristics. With the comprehensive data, the machine learning model can possibly be built.

References
Chen, Kuan-Fu (2020), “HRV sepsis dataset”, Mendeley Data, V1, doi: 10.17632/5tgk53r4v5.1

namespace DataDictionary\HRV;

【Mean.rate】: mean heart rate.
【Coefficient.of.variation】: A measure of the variability of heart rate.
【LF.HF.ratio.LombScargle】: LF (Low Frequency) to HF (High Frequency) ratio calculated using Lomb-Scargle power spectral analysis, often related to autonomic nervous system activity.
【DFA.Alpha.1 and DFA.Alpha.2】: Detrended Fluctuation Analysis alpha values.
【Largest.Lyapunov.exponent】 and 【Correlation.dimension】: Measures related to chaos theory and nonlinear dynamics.
【Power.Law.Slope.LombScargle】 and 【Power.Law.Y.Intercept.LombScargle】: Parameters related to power-law behavior in the Lomb-Scargle spectrum.
【Multiscale.Entropy】: A measure of signal complexity at multiple scales.
【VLF.Power.LombScargle】: Very Low-Frequency power calculated using Lomb-Scargle analysis.
【shannEn】: Shannon Entropy, a measure of signal randomness.
【PSeo】, 【Teo】, 【SymDp0_2】, 【SymDp1_2】, 【SymDp2_2】, 【SymDfw_2】, 【SymDse_2】, 【SymDce_2】: Various complexity measures and symbolic dynamics parameters.
【KLPE】: Kullback-Leibler Permutation Entropy.
【AsymI】: Asymmetry Index, possibly related to HRV asymmetry.
【Hurst.exponent】: A measure of long-term memory in time series data.


