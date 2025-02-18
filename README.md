# CF-AIDS-Comprehensive-Frequency-Agnostic-Intrusion-Detection-System-on-In-Vehicle-Network

Many studies have focused on obtaining high accuracy in the design of Intrusion Detection Systems (IDS) for in-vehicle networks, neglecting the significance of different intensive packet injection techniques. Because of their reliance on scenario-specific training datasets, these IDSs are vulnerable to failing to detect real-world attacks. This study implemented deep learning (DL)–based classification for intrusion detection using a Gated Recurrent Unit (GRU) while considering various intrusion frequencies. Different intrusion frequencies are comprehensively addressed with frequency-agnostic intrusion and resolved by generalizing features for DL input through time series segmentation and frequency domain conversion using Gabor filtering. For training purposes, five types of vehicle data are used, encompassing DoS, fuzzing, and replay attack scenarios. The accuracy range for mechanical version vehicles is typically between 95% and 100%. For electronic vehicles, it is around 90%. Considering the nature of this IDS system, it has been named a Comprehensive Frequency-Agnostic Intrusion Detection System (CF-AIDS). Although this IDS can perform better in all aspects, achieving more efficient results requires a larger amount of situational data.

Paper: [CF-AIDS_Comprehensive_Frequency-Agnostic_Intrusion_Detection_System_on_In-Vehicle_Network.pdf](https://github.com/user-attachments/files/17645759/CF-AIDS_Comprehensive_Frequency-Agnostic_Intrusion_Detection_System_on_In-Vehicle_Network.pdf)

BibTeX:

@article{islam2023cf,
  title={CF-AIDS: Comprehensive Frequency-Agnostic Intrusion Detection System on In-Vehicle Network},
  author={Islam, Md Rezanur and Sahlabadi, Mahdi and Kim, Keunkyoung and Kim, Yoonji and Yim, Kangbin},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE}
}
