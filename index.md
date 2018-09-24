

I am currently a PhD student at the [Institute for Communications Technology](https://www.ifn.ing.tu-bs.de/en/ifn/), Technische Universität Braunschweig, Germany. My research fields include **transcoded** (i.e., after encoding and decoding) **speech enhancement**, **deep learning methods**, and **robust speech and audio decoding**. [Here](https://www.ifn.ing.tu-bs.de/en/ifn/sp/zhao/) is my homepage in the university. 

I will briefly introduce my publications here. 

##  Publications
- **Enhancement of G.711-Coded Speech Providing Quality Higher Than Uncoded**

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt
  
  _accepted by ITG Conference on Speech Communication, Oct. 2018_
  
- **A CNN Postprocessor to Enhance Coded Speech** [[poster]](https://www.researchgate.net/publication/327844569_A_CNN_Postprocessor_to_Enhance_Coded_Speech)

  **Ziyue Zhao**, Samy Elshamy, Huijun Liu, Tim Fingscheidt
  
  _International Workshop on Acoustic Signal Enhancement (IWAENC), Sept. 2018_
  
  Abstract: Postprocessors can be advantageously used to enhance transcoded speech after the decoder on the receiver side. In this paper we present a CNN-based postprocessor applying cepstral domain features to enhance the transcoded speech for various narrowband and wideband codecs without any modification of these codecs. Simulations show that the proposed postprocessor is able to improve the coded speech quality (PESQ or WB-PESQ) by 0.25 MOS-LQO points for G.711, 0.26 points for G.726, 0.81 points for G.722, and 0.2 points for AMR-WB. Moreover, a superior performance is observed for the proposed postprocessor compared to an ITU-T-standardized postfilter for G.711. We also show that AMR-WB at lower bitrates together with our proposed postprocessor is able to exceed the speech quality of AMR-WB at higher bitrates without postprocessing (up to 3 modes higher).

- **Nonlinear Prediction of Speech by Echo State Networks** [[poster]](https://www.researchgate.net/publication/327605657_Nonlinear_Prediction_of_Speech_by_Echo_State_Networks)

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt

  **Best Student Paper Award** in _European Signal Processing Conference (EUSIPCO), Sept. 2018_
 
  Abstract: Speech prediction plays a key role in many speech signal processing and speech communication methods. While linear prediction of speech is well-studied, nonlinear speech prediction increasingly receives interest especially with the vast amount of new neural network topologies proposed recently. In this paper, nonlinear speech prediction is conducted by a special kind of recurrent neural network not requiring any training beforehand, the echo state network, which adaptively updates its output layer weights. Simulations show its superior performance compared to other well-known prediction approaches in terms of the prediction gain, exceeding all baselines in all conditions by up to 8 dB.
  
- **Convolutional Neural Networks to Enhance Coded Speech** [[paper]](https://arxiv.org/pdf/1806.09411.pdf)

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt
  
  _arXiv preprint arXiv:1806.09411, Jun. 2018_
 
  Abstract: Enhancing coded speech suffering from far-end acoustic background noise, quantization noise, and potentially transmission errors, is a challenging task. In this work we propose two postprocessing approaches applying convolutional neural networks (CNNs) either in the time domain or the cepstral domain to enhance the coded speech without any modification of the codecs. The time domain approach follows an end-to-end fashion, while the cepstral domain approach uses analysis-synthesis with cepstral domain features. The proposed postprocessors in both domains are evaluated for various narrowband and wideband speech codecs in a wide range of conditions. The proposed postprocessor improves speech quality (PESQ) by up to 0.25 MOS-LQO points for G.711, 0.30 points for G.726, 0.82 points for G.722, and 0.26 points for adaptive multirate wideband codec (AMR-WB). In a subjective CCR listening test, the proposed postprocessor on G.711-coded speech exceeds the speech quality of an ITU-T-standardized postfilter by 0.36 CMOS points, and obtains a clear preference of 1.77 CMOS points compared to G.711, even en par with uncoded speech. The source code for the cepstral domain approach to enhance G.711-coded speech is made available in the [Github project](https://github.com/ifnspaml/Enhancement-Coded-Speech).
  
- **Improving Vector Quantization-Based Decoders for Correlated Processes in Error-Free Transmission** [[paper]](https://www.researchgate.net/profile/Ziyue_Zhao/publication/309321915_Improving_Vector_Quantization-Based_Decoders_for_Correlated_Processes_in_Error-Free_Transmission/links/5809eec908ae3a04d624f3aa.pdf)

  **Ziyue Zhao**, Sai Han, Tim Fingscheidt

  _ITG Conference on Speech Communication, Oct. 2016_

  Abstract: Low bit rate vector quantization (VQ) is omnipresent in today’s media transmission. With IP-based transmission the situation is that source-coded bits are typically either lost/deleted as a whole frame/packet, or they are received correctly. Assuming correctly received VQ symbols we show how to exploit vector-to-vector (i.e., residual temporal) redundancy at the decoder side for an improved reconstruction. It turns out that a feedforward neural network is an effective means for predicting better reconstruction vectors at the receiver in a system-compatible fashion, gaining up to 1 dB SNR depending on signal correlation and bit rate.



