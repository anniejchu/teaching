# COMPUTER AUDITION (AKA Computational Auditory Scene Analyis), Northwestern University EECS 495-??? fall 2018
## Loctation: Technological Institute L168
## Day/Time: Mondays, 3:00pm - 5:50pm
## Instructor: [Bryan Pardo](http://bryanpardo.com)
## Course Description
This course studies how a computational system can organize sound into perceptually meaningful elements. Problems in this field include source separation (splitting audio mixtures into individual sounds), source identification (labeling a source sound), and streaming (finding which sounds belong to a single explanation/event). This course is an advanced graduate course covering current research in the field.

## Course Calendar


| Week|Date        | Topic                          |           
|----:|------------|--------------------------------|
|1  | Oct  1    | Basics of audition and digital signal processing
|2  | Oct  8    | Basics of deep learning (convolutional nets, LSTMs)
|3  | Oct  15   | Auditory representations (Patterson, Shamma, Stoter, Pishdadian)
|4  | Oct  22   | Source Separation Algorithms 
|5  | Oct  29   | Source Separation Algorithms 
|6  | Nov  5    | Generating Audio
|7  | Nov  12   | Speech Recognition 
|8  | Nov  19   | ** NO CLASS: PROF. PARDO IS AT DCASE WORKSHOP **
|9  | Nov  26   | Audio Scene Labeling  
|10 | Dec  3    | Audio Scene Labeling
|11 | Dec  10   | Attention Models 


## Course assignments
### Written Paper reviews: 20 points 
Every 2 weeks, you will submit a set of 4 single-page overviews of papers/chapters you read. Each review will be worth 1 point.  

### Class Paper Presentations: 20 points
Twice during the course of the term, you will be the lead person discussing a paper in class. This will mean you haven't just read the paper, but you've read related work, really understand it and can give a brief presentation of the paper (including slides) and then lead a discussion about it. 

### Class participation: 20 points
Each week (even weeks when you're not presenting) you're expected to show up, have read the papers and be able to discuss ideas. Every week you show up and substantially contribute to the discussion, you get 2 points. If you don't show up or you don't say anything that week, you don't get the 2 points. 

### Written Literature review and intro: 40 points
The final assignment in the class is to have written a literature review and introduction to a research paper in an ACM format. 

## Course Reading   
### Week 1: Oct 1
[Bregman's Auditory Scene Analysis, Chapter 1](http://www.cs.northwestern.edu/~pardo/courses/casa/papers/asa_chapter_1.pdf)

[Brown and Wang's Computational Auditory Scene Analysis, Chapter 1](http://www.cs.northwestern.edu/~pardo/courses/casa/papers/casa_chapter_1.pdf)

### Week 2: Oct 8 
[Chapter 4 from Machine Learning](http://www.cs.northwestern.edu/~pardo/courses/eecs349/readings/chapter4-ml.pdf)

[Convolutional Networks for Images, Speech, and Time-Series](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.32.9297)

[Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

[stretch goal: Chapter 9 of Deep Learning: Convolutional Networks](http://www.deeplearningbook.org/)

[stretch goal: Long Term Short Term Memory](casa/HorchreiterSchmidhuber_LSTM.pdf)

### Week 3: Oct 15  Auditory Representations

Prem: [Summary statistics in auditory perception ](http://mcdermottlab.mit.edu/papers/McDermott_Schemitsch_Simoncelli_2013_summary_statistics.pdf)

Fatemeh: [Multiresolution spectrotemporal analysis of complex sounds](https://ir.nctu.edu.tw/bitstream/11536/13455/1/000231210500036.pdf)

Fatemeh: [Multi-resolution Common Fate Transform](casa/mcft_revision2.pdf)

<!--[Spectral Shape Analysis in the Central Auditory System](http://www.cs.northwestern.edu/~pardo/courses/casa/papers/Spectral%20Shape%20Analysis%20in%20the%20Central%20Auditory%20System%20-%20shamma.pdf) -->


### Week 4: Oct 22  More Auditory Representations & Source Separation


Prof Pardo: [Recovering sound sources from embedded repetition](http://mcdermottlab.mit.edu/papers/McDermott_Wrobleski_Oxenham_2011_source_repetition.pdf)

Madhav: [REPET](http://music.eecs.northwestern.edu/publications/Rafii-Liutkus-Pardo%20-%20REPET%20for%20Background-Foreground%20Separation%20in%20Audio%20-%20Springer%202014.pdf)

Prem: [2DFT](http://music.eecs.northwestern.edu/publications/waspaa2017_seetharaman_pishdadian_pardo.pdf)

### Week 5: Oct 29  Source Separation Algorithms

#### Non-negative matrix factorization

Conway: [Algorithms for Non-negative Matrix Factorization](http://papers.nips.cc/paper/1861-algorithms-for-non-negative-matrix-factorization)

Willl (3 L's is cool): [Learning mid-level auditory codes from natural sound statistics](http://mcdermottlab.mit.edu/papers/Mlynarski_McDermott_2017_learning_mid_level_codes.pdf)

[SIMULTANEOUS SEPARATION AND SEGMENTATION IN LAYERED MUSIC](http://music.cs.northwestern.edu/publications/seetharaman_pardo_ismir16.pdf)

#### Deep embedding space source separation
Nathan: [Deep clustering: Discriminative embeddings for segmentation and separation](http://ieeexplore.ieee.org/abstract/document/7471631/)

Brian: [DEEP ATTRACTOR NETWORK FOR SINGLE-MICROPHONE SPEAKER SEPARATION](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5805382/)

#### additional materials
[Alternative Objective Functions for Deep Clustering](http://www.merl.com/publications/docs/TR2018-005.pdf)

### Week 6: Nov 5  Generating audio 

#### Wavenet and descendents
Vyas: [WaveNet: A Generative Model for Raw Audio](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)

Mike: [Deep Voice: Real-time Neural Text-to-Speech](https://arxiv.org/pdf/1702.07825.pdf)

Max: [Parallel Wavenet](http://proceedings.mlr.press/v80/oord18a.html)

#### Also of interest
Brian: [Deep Cross-Modal Audio-Visual Generation](https://arxiv.org/abs/1704.08292)

#### Wavenet alternatives
[SampleRNN: Bengio's take on generating speech](https://arxiv.org/pdf/1612.07837.pdf)

[Tacotron 2 is the 2018 speech generation system from Google](https://arxiv.org/abs/1712.05884)

[Towards End-to-End Prosody Transfer for Expressive Speech Synthesis with Tacotron](https://arxiv.org/abs/1803.09047)

#### Additional materials 
[Lyrebird](https://lyrebird.ai/) commercializes deep learning speech generation

[The Deep Voice Talk at ICML](https://vimeo.com/240608423)

### Week 7: Nov 12	 Speech Recognition: traditional 

Vyas: [Highway Long Short-Term Memory RNNs for Distant Speech Recognition](https://arxiv.org/abs/1510.08983)

El Pardo: [Connectionist temporal classification (CTC): labelling unsegmented sequence data with recurrent neural networks](https://www.cs.toronto.edu/~graves/icml_2006.pdf)

Mike: [Towards End-to-End Speech Recognition with Deep Convolutional Neural Networks](https://arxiv.org/abs/1701.02720)

#### Additional materials

[The Rabiner HMM tutorial](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=18626) (useful for CTC understanding)

[Intuitively understanding Connectionist Temporal Classification](https://towardsdatascience.com/intuitively-understanding-connectionist-temporal-classification-3797e43a86c)

[Towards End-to-End Speech Recognition with Recurrent Neural Networks](http://proceedings.mlr.press/v32/graves14.pdf) (the precursor to the recognition with convolutional neural nets paper)

[Highway Networks](https://arxiv.org/pdf/1505.00387.pdf) (useful for understanding Highway LSTMs)


### Week 8: Nov 19  ** NO CLASS BUT GO AHEAD AND READ MORE ON SPEECH, IF YOU'RE INTERESTED  **

[Building End-to-End Dialogue Systems Using Generative Hierarchical Neural Network Models](http://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11957/12160)

[Dynamic Layer Normalization for Adaptive Neural Acoustic Modeling in Speech Recognition](https://arxiv.org/abs/1707.06065)

[Analysis of I-vector Length Normalization in Speaker Recognition Systems](https://pdfs.semanticscholar.org/1323/72db185b502e58765104c1465985fcab053a.pdf)


### Week 9: Nov 26		General Audio Scene Labeling

Sean: [SoundNet: Learning Sound Representations from Unlabeled Video](https://projects.csail.mit.edu/soundnet/)

???: [Unsupervised Cross-Modal Deep-Model Adaptation for Audio-Visual Re-Identification With Wearable Cameras](http://openaccess.thecvf.com/content_ICCV_2017_workshops/w8/html/Brutti_Unsupervised_Cross-Modal_Deep-Model_ICCV_2017_paper.html)

BongJun: [A Human-in-the-Loop System for Sound Event Detection and Annotation](http://music.eecs.northwestern.edu/publications/kim_pardo_tiis_2018.pdf)

Nathan: [UNSUPERVISED LEARNING OF SEMANTIC AUDIO REPRESENTATIONS](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46665.pdf)


### Week 10: Dec 3 	More Scene labeling + Interactive Sound Search

BongJun: [Convolutional Recurrent Neural Networks for Polyphonic Sound Event Detection](https://arxiv.org/pdf/1702.06286.pdf)


#### Comparing architectures for scene labeling
Will: [CNN Architectures for Large-Scale Audio Classification](https://ai.google/research/pubs/pub45611)

#### Additional materials
[(VGG Net) Very Deep Convolutional Networks for Large-Scale Image Recognition ](https://arxiv.org/abs/1409.1556)

[(Alex Net) ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)

[(Inception)Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567)

Conway: [(ResNet)Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

#### Query by example audio search systems

Madhav: [Siamese Style Convolutional Neural Networks for Sound Search by Vocal Imitation](https://ieeexplore.ieee.org/document/8453811)


### Week 11: DEC 10 	Attention Models 
Max: [Listen, Attend and Spell](https://arxiv.org/pdf/1508.01211.pdf)

Sean: [Describing Videos by Exploiting Temporal Structure](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Yao_Describing_Videos_by_ICCV_2015_paper.html)

Fatemeh:[Modeling attention-driven plasticity in auditory cortical receptive fields](https://www.frontiersin.org/articles/10.3389/fncom.2015.00106/full)

#### Additional Materials
[Modelling Auditory Attention](http://rstb.royalsocietypublishing.org/content/372/1714/20160101)

[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://www.jmlr.org/proceedings/papers/v37/xuc15.pdf)




