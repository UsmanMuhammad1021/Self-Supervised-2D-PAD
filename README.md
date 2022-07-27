## [Self-supervised 2D face presentation attack detection via temporal sequence sampling](https://www.sciencedirect.com/science/article/pii/S0167865522000605)
#### Authors: Usman Muhammad, Zitong Yu, and Jukka Komulainen
For any problem in running the code, please contact me through following emails: usman@mail.bnu.edu.cn  or muhammad.usman@oulu.fi
##

#### Journal: [PATTERN RECOGNITION LETTERS](https://www.journals.elsevier.com/pattern-recognition-letters) - Elsevier [Special Issue on Biometric Presentation Attacks: handcrafted features versus deep learning approaches (BioPAth)]
##

### Highlights
• Inter-frame 2D affine motion compensation is exploited for detecting 2D face artefacts.

• Temporal Sequence Sampling (TSS) is proposed to encode a video into a single image.

• A self-supervised learning scheme is presented for face presentation attack detection.

• Promising generalization is achieved in cross-database setup on public benchmarks.

### Abstract
Conventional 2D face biometric systems are vulnerable to presentation attacks performed with different face artefacts, e.g. printouts, video-replays and wearable 3D masks. The research focus in face presentation attack detection (PAD) has been recently shifting towards end-to-end learning of deep representations directly from annotated data rather than designing hand-crafted (low-level) features. However, even the state-of-the-art deep learning based face PAD models have shown unsatisfying generalization performance when facing previously unseen attacks and acquisition conditions due to lack of representative training and tuning data available in the existing public benchmarks. To alleviate this issue, we propose a video pre-processing technique called Temporal Sequence Sampling (TSS) for 2D face PAD by removing the estimated inter-frame 2D affine motion in the view and encoding the appearance and dynamics of the resulting smoothed video sequence into a single RGB image. Furthermore, we leverage the features of a convolutional neural network (CNN) by introducing a self-supervised representation learning scheme, where the labels are automatically generated by the TSS method as the stabilized frames accumulated over video clips of different temporal lengths provide the supervision. The learnt feature representations are then fine-tuned for the downstream task using labeled face PAD data. Our extensive experiments on four public benchmarks, namely Replay-Attack, MSU-MFSD, CASIA-FASD and OULU-NPU, demonstrate that the proposed framework provides state-of-the-art generalization capability and encourage further study in this domain.

#### The source codes are available to the research community. If you are using the code, please cite the following paper:                              
Muhammad, Usman; Yu, Zitong; Komulainen, Jukka (2021): Self-supervised 2D face presentation attack detection via temporal sequence sampling. TechRxiv.  

### BibTeX
@article{muhammad2022self,
  title={Self-supervised 2D face presentation attack detection via temporal sequence sampling},
  author={Muhammad, Usman and Yu, Zitong and Komulainen, Jukka},
  journal={Pattern Recognition Letters},
  volume={156},
  pages={15--22},
  year={2022},
  publisher={Elsevier}
}

### Links
• Main link: https://www.sciencedirect.com/science/article/pii/S0167865522000605

• Preprint: https://doi.org/10.36227/techrxiv.16917526.v1 

