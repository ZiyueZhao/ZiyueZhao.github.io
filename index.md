

I am currently a PhD student at the [Institute for Communications Technology](https://www.ifn.ing.tu-bs.de/en/ifn/), Technische Universität Braunschweig, Germany. My research fields include **speech enhancement**, **deep learning methods**, and **improved speech and audio decoding**. [Here](https://www.ifn.ing.tu-bs.de/en/ifn/sp/zhao/) is my homepage in the university. 

I will briefly introduce my publications here. 

##  Publications
- **A Perceptual Weighting Filter Loss for DNN Training in Speech Enhancement** [[paper]](https://arxiv.org/pdf/1905.09754.pdf)

  **Ziyue Zhao**, Samy  Elshamy, Tim Fingsheidt
  
  _Workshop on Applications of Signal Processing to Audio and Acoustics (WASPAA), New Paltz, NY, US, Oct. 2019_
  
  Abstract: Single-channel speech enhancement with deep neural networks (DNNs) has shown promising performance and is thus intensively being studied. In this paper, instead of applying the mean squared error (MSE) as the loss function during DNN training for speech enhancement, we design a perceptual weighting filter loss motivated by the weighting filter as it is employed in analysis-by-synthesis
speech coding, e.g., in code-excited linear prediction (CELP). The experimental results show that the proposed simple loss function
improves the speech enhancement performance compared to a reference DNN with MSE loss in terms of perceptual quality and noise attenuation. The proposed loss function can be advantageously applied to an existing DNN-based speech enhancement system, without modification of the DNN topology for speech enhancement.

- **Learning to Dequantize Speech Signals by Primal-dual Networks: an Approach for Acoustic Sensor Networks**

  Christoph Brauer, **Ziyue Zhao**, Dirk Lorenz, Tim Fingscheidt
  
  _International Conference on Acoustics, Speech and Signal Processing (ICASSP), Brighton, UK, May 2019_
  
  Abstract: We introduce a method to improve the quality of simple scalar quantization in the context of acoustic sensor networks by combining ideas from sparse reconstruction, artificial neural networks and weighting filters. We start from the observation that optimization methods based on sparse reconstruction resemble the structure of a neural network. Hence, building upon a successful enhancement method, we unroll the algorithms and use this to build a neural network which we train to obtain enhanced decoding. In addition, the weighting filter from code-excited linear predictive (CELP) speech coding is integrated into the loss function of the neural network, achieving perceptually improved reconstructed speech. Our experiments show that our proposed trained methods allow for better speech reconstruction than the reference optimization methods.

- **Convolutional Neural Networks to Enhance Coded Speech** [[paper]](https://ieeexplore.ieee.org/document/8579579)

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt
  
  _IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 27, no.4, Apr. 2019_
 
  Abstract: Enhancing coded speech suffering from far-end acoustic background noise, quantization noise, and potentially transmission errors, is a challenging task. In this work we propose two postprocessing approaches applying convolutional neural networks (CNNs) either in the time domain or the cepstral domain to enhance the coded speech without any modification of the codecs. The time domain approach follows an end-to-end fashion, while the cepstral domain approach uses analysis-synthesis with cepstral domain features. The proposed postprocessors in both domains are evaluated for various narrowband and wideband speech codecs in a wide range of conditions. The proposed postprocessor improves speech quality (PESQ) by up to 0.25 MOS-LQO points for G.711, 0.30 points for G.726, 0.82 points for G.722, and 0.26 points for adaptive multirate wideband codec (AMR-WB). In a subjective CCR listening test, the proposed postprocessor on G.711-coded speech exceeds the speech quality of an ITU-T-standardized postfilter by 0.36 CMOS points, and obtains a clear preference of 1.77 CMOS points compared to G.711, even en par with uncoded speech. The source code for the cepstral domain approach to enhance G.711-coded speech is made available in the [Github project](https://github.com/ifnspaml/Enhancement-Coded-Speech).

- **Enhancement of G.711-Coded Speech Providing Quality Higher Than Uncoded** [[paper]](https://www.researchgate.net/publication/328416287_Enhancement_of_G711-Coded_Speech_Providing_Quality_Higher_Than_Uncoded)[[poster]](https://www.researchgate.net/publication/328416351_Enhancement_of_G711-Coded_Speech_Providing_Quality_Higher_Than_Uncoded)

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt
  
  _ITG Conference on Speech Communication, Oldenburg, Germany, Oct. 2018_
  
  Abstract: The speech quality of the worldwide mostly used speech codec ITU-T G.711 can be advantageously enhanced on the decoder side without modifying the codec itself. In this paper we present an enhancement approach for G.711-coded speech based on a convolutional neural network (CNN) employing cepstral domain features in a system-compatible fashion. In a subjective CCR listening test, the proposed enhancement approach exceeds the speech quality of an ITU-T-standardized postfilter by 0.36 CMOS points, and improves G.711-coded speech by a clear 1.77 CMOS points. The proposed CNN-based enhancement approach even achieves a significant 0.18 CMOS points improvement when compared to uncoded speech, a surprising result which, to the best of our knowledge, has never been seen before. 
  
- **A CNN Postprocessor to Enhance Coded Speech** [[paper]](https://www.researchgate.net/publication/328079810_A_CNN_Postprocessor_to_Enhance_Coded_Speech)[[poster]](https://www.researchgate.net/publication/327844569_A_CNN_Postprocessor_to_Enhance_Coded_Speech)

  **Ziyue Zhao**, Samy Elshamy, Huijun Liu, Tim Fingscheidt
  
  _International Workshop on Acoustic Signal Enhancement (IWAENC), Tokyo, Japan, Sept. 2018_
  
  Abstract: Postprocessors can be advantageously used to enhance transcoded speech after the decoder on the receiver side. In this paper we present a CNN-based postprocessor applying cepstral domain features to enhance the transcoded speech for various narrowband and wideband codecs without any modification of these codecs. Simulations show that the proposed postprocessor is able to improve the coded speech quality (PESQ or WB-PESQ) by 0.25 MOS-LQO points for G.711, 0.26 points for G.726, 0.81 points for G.722, and 0.2 points for AMR-WB. Moreover, a superior performance is observed for the proposed postprocessor compared to an ITU-T-standardized postfilter for G.711. We also show that AMR-WB at lower bitrates together with our proposed postprocessor is able to exceed the speech quality of AMR-WB at higher bitrates without postprocessing (up to 3 modes higher).

- **Nonlinear Prediction of Speech by Echo State Networks** [[paper]](https://www.researchgate.net/publication/327582550_Nonlinear_Prediction_of_Speech_by_Echo_State_Networks_EURASIP_Best_Student_Paper_Award)[[poster]](https://www.researchgate.net/publication/327605657_Nonlinear_Prediction_of_Speech_by_Echo_State_Networks)

  **Ziyue Zhao**, Huijun Liu, Tim Fingscheidt

  **Best Student Paper Award** in _European Signal Processing Conference (EUSIPCO), Rome, Italy, Sept. 2018_
 
  Abstract: Speech prediction plays a key role in many speech signal processing and speech communication methods. While linear prediction of speech is well-studied, nonlinear speech prediction increasingly receives interest especially with the vast amount of new neural network topologies proposed recently. In this paper, nonlinear speech prediction is conducted by a special kind of recurrent neural network not requiring any training beforehand, the echo state network, which adaptively updates its output layer weights. Simulations show its superior performance compared to other well-known prediction approaches in terms of the prediction gain, exceeding all baselines in all conditions by up to 8 dB.

- **Improving Vector Quantization-Based Decoders for Correlated Processes in Error-Free Transmission** [[paper]](https://www.researchgate.net/profile/Ziyue_Zhao/publication/309321915_Improving_Vector_Quantization-Based_Decoders_for_Correlated_Processes_in_Error-Free_Transmission/links/5809eec908ae3a04d624f3aa.pdf)

  **Ziyue Zhao**, Sai Han, Tim Fingscheidt

  _ITG Conference on Speech Communication, Paderborn, Germany, Oct. 2016_

  Abstract: Low bit rate vector quantization (VQ) is omnipresent in today’s media transmission. With IP-based transmission the situation is that source-coded bits are typically either lost/deleted as a whole frame/packet, or they are received correctly. Assuming correctly received VQ symbols we show how to exploit vector-to-vector (i.e., residual temporal) redundancy at the decoder side for an improved reconstruction. It turns out that a feedforward neural network is an effective means for predicting better reconstruction vectors at the receiver in a system-compatible fashion, gaining up to 1 dB SNR depending on signal correlation and bit rate.



