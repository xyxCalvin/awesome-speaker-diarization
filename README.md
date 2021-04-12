# awesome-speaker-diarization
## DataSet
- [Spot the conversation: speaker diarisation in the wild](https://arxiv.org/abs/2007.01216) (Chung J S, Huh J, Nagrani A, et al.(VGG))
A free speaker diarization dataset.(Large dataset with overlapping speeches and background noise)
## Audio-only
- [An End-to-End Speaker Diarization Service for improving Multimedia Content Access](https://nem-initiative.org/wp-content/uploads/2020/07/1-4-an_end_to_end_speaker_diarization_service_for_improving_multimedia_content_access.pdf) (MARTÍN-GUTIÉRREZ, D. A. V. I. D., et al.)

An introduction to basic methods for speaker diarization. (statistic based and DL based)

- [Target-Speaker Voice Activity Detection: a Novel Approach for Multi-Speaker Diarization in a Dinner Party Scenario](https://arxiv.org/abs/2005.07272) (Medennikov I, Korenevsky M, Prisyach T, et al. )
TS-VAD method for speaker diarization on audio model. (signal/ multi channel & signal/ multi speaker)

- [Front-End Factor Analysis for Speaker Verification](https://ieeexplore.ieee.org/abstract/document/5545402/) (Dehak N, Kenny P J, Dehak R, et al. IEEE, 2010)
i-vector, a statistic methods for audio representation (audio modality) (i-vector represent a given utterance with a single fixed-dimensional feature vector.)

- [Deep Neural Networks for Small Footprint Text-Dependent Speaker Verification](https://ieeexplore.ieee.org/abstract/document/6854363) (Variani E, Lei X, McDermott E, et al. ICASSP, 2014)
d-vector, a deep learning based method for audio representation (audio modality)

- [A Review of Speaker Diarization: Recent Advances with Deep Learning](https://arxiv.org/abs/2101.09624) (Park T J, Kanda N, Dimitriadis D, et al.)
A review of deep leaning based speaker diarization. (mostly on audio modality)

- [Speaker Diarization with Region Proposal Network](https://arxiv.org/abs/2002.06220) (Huang Z, Watanabe S, Fujita Y, et al. ICASSP, 2020)
Migrate the Faster R-CNN method


- [Speaker Diarization with LSTM](https://arxiv.org/abs/1710.10468) (Wang Q, Downey C, Wan L, et al. ICASSP, 2018) 
Combine LSTM-based embeddings with spectral clustering


- [Low-dimensional speech representation based on Factor Analysis and its applications](http://people.csail.mit.edu/sshum/talks/ivector_tutorial_interspeech_27Aug2011.pdf) (Dehak N, Shum S. )
Tutorial for i-vectors


- [Fully supervised speaker diarization](https://ieeexplore.ieee.org/abstract/document/8683892) (Zhang A, Wang Q, Zhu Z, et al. ICASSP, 2019)
UIS-RNN: A fully supervised approach which handles an unbound number of speakers using an online generative process.

- [Supervised Online Diarization with Sample Mean Loss for Multi-Domain Data](https://ieeexplore.ieee.org/abstract/document/9053477) (Fini E, Brutti A. ICASSP, 2020)
Enhance UIS-RNN.




## Multi-modality
- [Self-supervised learning for audio-visual speaker diarization](https://ieeexplore.ieee.org/abstract/document/9054376) (Ding Y, Xu Y, Zhang S X, et al. ICASSP, 2020)
An audio-visual methods for speaker diarization, based one contrast learning.

- [Joint Speech Recognition and Speaker Diarization via Sequence Transduction](https://arxiv.org/abs/1907.05337) (Shafey L E, Soltau H, Shafran I)
Based on RNN-T structure, combine text content and voice point information.

- [Look Who's Not Talking](https://arxiv.org/abs/2011.14885) (Kwon Y, Heo H S, Huh J, et al. (VGG))
Since the speaker embeddings are able to discriminate one person's speech from another, it might be able to discriminate speech from non-speech.


 ## Audio-Visual Localization
 - [Audio-Visual Event Localization in Unconstrained Videos](https://openaccess.thecvf.com/content_ECCV_2018/html/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.html) (Tian Y, Shi J, Li B, et al. ECCV, 2018)
 Cross modal attention for localization. Aligned frames' features are closer.
 
 - [Dual Attention Matching for Audio-Visual Event Localization](https://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Dual_Attention_Matching_for_Audio-Visual_Event_Localization_ICCV_2019_paper.html) (Wu Y, Zhu L, Yan Y, et al. IEEE, 2019)
 Combine local feature and global feature to estimate relevant frames.
 
 - [Learning to Localize Sound Sources in Visual Scenes](https://openaccess.thecvf.com/content_cvpr_2018/html/Senocak_Learning_to_Localize_CVPR_2018_paper.html) (Senocak A, Oh T H, Kim J, et al. IEEE, 2018)
Cross modal attention and contrastive learning. 

- [Multiple Sound Sources Localization from Coarse to Fine](https://link.springer.com/content/pdf/10.1007/978-3-030-58565-5_18.pdf) (Qian R, Di Hu H D, Wu M, et al.) 
Leverage CAM to sound source localization.
 
