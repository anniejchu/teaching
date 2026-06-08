# DEEP LEARNING, Northwestern University EECS 396/496 Fall 2020
### Loctation: ONLINE ON ZOOM
### Day/Time: Tuesday/Thursday, 4:20pm - 5:40pm
### Instructor: [Bryan Pardo](http://bryanpardo.com)
### Course Description
In this course students will study deep learning architectures: perceptrons, multi layer perceptrons, convolutional networks, recurrent neural networks (LSTMs, GRUs), Attention networks, Auto-encoders, Variational Auto Encoders (VAEs)They will read original research papers that describe the algorithms and how they have been applied to fields like computer vision, machine translation, automatic speech recognition, and audio event recognition. They will build a final project that shows their learning.

### Course Calendar

| Week|Date        | Topic                          |Deliverable           | Points|
|----:|------------|--------------------------------|----------------------|---------------------------:|
|0 | Sep 17 - Nov 24   |          |Class Participation | 10 |
|1 | Thu Sep 17   | Basics of the course         | | |
|2 | Tue Sep 22   | The perceptron               | | |
|2 | Thu Sep 24   | Backpropagation of error     | | |
|3 | Tue Sep 29   | Sigmoid function & MLPs      |Four Readings | 12 |
|3 | Thu Oct 1    | Optimization,loss-landscapes | | |
|4 | Tue Oct 6    | Regularization               | | |
|4 | Thu Oct 8    | Convolutional Networks       | | |
|5 | Tue Oct 13   | Final projects               |Four Readings | 12 |
|5 | Thu Oct 15   | MIDTERM                      |Midterm       | 12 |
|6 | Tue Oct 20   | Recurrent networks           |Group Selection | 5 |
|6 | Thu Oct 22   | LSTM & GRUs                  | | |
|7 | Tue Oct 27   | Attention networks           |Four Readings | 12 |
|7 | Thu Oct 29   | Adversarial robustness       |Project proposal | 5 |
|8 | Tue Nov 3    | GANs                         | | |
|8 | Thu Nov 5    | Reinforcement Learning       | | |
|9 | Tue Nov 10   | Deep Reinforcement Learning  |Four Readings | 12 |
|9 | Thu Nov 12   | Autoencoders                 | | |
|10 | Tue Nov 17  | Variational Autoencoders     |Project update | 5 |
|10 | Thu Nov 19  | DL in the world              |Project meetings| 5 |
|11 | Tue Nov 24  | Current DL projects at NU    | | |
|11 | Thu Nov 26  | THANKSKIVING                 | | |
|12 | Tue Dec 1   | no class, work on projects   |3 Xtra Credit Readings | 9 |
|12 | Thu Dec 3   | no class, work on projects   | | |
|13 | Tue Dec 8   | FINAL PROJECTS DUE           |Projet video | 10 |

### About "class participation"
Class participation will be measured in the following ways: Asking questions in lecture, helping classmates online, coming to office hours. Do all 3, get 10 points.

### Helpful Programming Links
[Anaconda: The most popular python distro for machine learning](https://www.continuum.io/downloads)

[Scikit Learn: the most popular machine learning python package](http://scikit-learn.org/stable/)

[Tensorflow: the most popular python DNN package](https://www.tensorflow.org/)

[Keras: A nice python API for Tensorflow](https://keras.io/)

[Pytorch: I'd recommend this](http://pytorch.org/)

[MXNET: Apache's open source DL package](https://mxnet.apache.org/versions/1.6/get_started?)

[Dive Into Deep Learning](http://d2l.ai/index.html) Provides example code and instruction for how to write DL models in Pytorch, Tensorflow and MXNet.

### Computing Resources

[Amazon's SageMaker](https://aws.amazon.com/sagemaker/pricing/) offers hundres of free hours for newbies.

[Google's Colab](https://colab.research.google.com/notebooks/intro.ipynb) offers free GPU time and a nice environment for running Jupyter notebook-style projects.
For $10 per month, you also get priority access to GPUs and TPUs.

### Course Reading
#### Week 1: The pre-history
[The very first neural net paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.335.3398&rep=rep1&type=pdf)

[Chapter 1 of Parallel Distributed Processing](http://cognet.mit.edu/book/parallel-distributed-processing)


#### Week 2: The Multilayer Perceptron
[Chapter 4 of Machine Learning ](http://www.cs.northwestern.edu/~pardo/courses/eecs349/readings/chapter4-ml.pdf)

[Chapter 6 of Deep Learning](http://www.deeplearningbook.org/)

[Blog: A hacker's guide to neural nets](http://karpathy.github.io/neuralnets/)


#### Week 3:  Regularization and Optimization

[Chapters 7 and 8 of the Deep Learning Book](http://www.deeplearningbook.org/)

[Why Momentum Really Works](http://distill.pub/2017/momentum/)

[Dropout: A Simple Way to Prevent Neural Networks from Overfitting](https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf)

[Identifying and attacking the saddle point problem in high-dimensional non-convex optimization](https://arxiv.org/abs/1406.2572)

[Batch Normalization](https://arxiv.org/abs/1502.03167)

[Self-normalizing networks](https://arxiv.org/abs/1706.02515)

[A blog describing how to easily implement Self-normalizing networks](https://becominghuman.ai/paper-repro-self-normalizing-neural-networks-84d7df676902)


#### Week 4: Convolutional Networks

[Chapter 9 of Deep Learning: Convolutional Networks](http://www.deeplearningbook.org/)

[Generalization and Network Design Strategies](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.476.479&rep=rep1&type=pdf)

[Convolutional Networks for Images, Speech, and Time-Series](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.32.9297)

[Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842)

[Visualizing and Understanding Convolutional Networks](https://arxiv.org/pdf/1311.2901v3.pdf)

#### Week 5: Residual Networks
[Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)

Huayi: [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385v1.pdf)

[Fast R-CNN (Deep ResNets uses this)](https://arxiv.org/pdf/1504.08083.pdf)

#### Week 6: Recurrent Networks
[Chapter 10 of Deep Learning](http://www.deeplearningbook.org/)

[A tutorial on Back Propagation Through Time](http://www.wildml.com/2015/10/recurrent-neural-networks-tutorial-part-3-backpropagation-through-time-and-vanishing-gradients/)

[On the Difficulties of Training Recurrent Networks](http://proceedings.mlr.press/v28/pascanu13.pdf)

[Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

[Long Term Short Term Memory](https://www.researchgate.net/publication/13853244_Long_Short-term_Memory)

[Deep Visual-Semantic Alignments for Generating Image Descriptions](https://arxiv.org/pdf/1412.2306v2.pdf) 

[Bidirectional RNNs: NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE](https://arxiv.org/pdf/1409.0473.pdf)

[Experiments in Handwriting with a LSTM Neural Network](http://distill.pub/2016/handwriting/)

[The paper that introduced GRUs: Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/abs/1406.1078)

[Empirical Evaluation of Gated Recurrent Neural Networks on Sequence Modeling](https://arxiv.org/abs/1412.3555)

Yiming: [Learning to Forget: Continual Prediction with LSTM](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.55.5709&rep=rep1&type=pdf)

[Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)

[The NIPS talk on Sequence to Sequence Learning](https://www.microsoft.com/en-us/research/video/nips-oral-session-4-ilya-sutskever/?from=http%3A%2F%2Fresearch.microsoft.com%2Fapps%2Fvideo%2F%3Fid%3D239083)

#### Week 7: Attention 
[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://www.jmlr.org/proceedings/papers/v37/xuc15.pdf)

[Listen, Attend and Spell](https://arxiv.org/pdf/1508.01211.pdf)

[Describing Videos by Exploiting Temporal Structure](http://www.cv-foundation.org/openaccess/content_iccv_2015/html/Yao_Describing_Videos_by_ICCV_2015_paper.html)

[Modelling Auditory Attention](http://rstb.royalsocietypublishing.org/content/372/1714/20160101)

[Attention is All You Need](https://arxiv.org/abs/1706.03762)

[The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) (This is a tutorial that explains the concepts in "Attention is All You Need")


#### Week 8: Generative Adversarial Networks (GANs) 

[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)

[Generative Adversarial Nets](https://arxiv.org/pdf/1406.2661v1.pdf)

[Julia Evans' walkthrough of generating adversarial examples](https://codewords.recurse.com/issues/five/why-do-neural-networks-think-a-panda-is-a-vulture)

[Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images](http://www.evolvingai.org/files/DNNsEasilyFooled_cvpr15.pdf)

#### Week 9: Autoencoders and Variational Auto Encoders (VAEs)

[Chapter 16 and 20 of  Deep Learning Book (just the bits on RBMs)](http://www.deeplearningbook.org/)

[Scaling Learning Algorithms towards AI](http://www.iro.umontreal.ca/~lisa/pointeurs/bengio+lecun_chapter2007.pdf)

[Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908)

#### Week 10: Reinforcement Learning

[Reinforcement Learning: An Introduction, Chapters 3 and 6](http://incompleteideas.net/sutton/book/bookdraft2016sep.pdf)

[My lecture notes on reinforcement learning (easier intro)](http://www.cs.northwestern.edu/~pardo/courses/eecs349/lectures/NU%20EECS%20349%20Fall%2009%20topic%2015%20-%20Reinforcement%20Learning.pdf)

[Attention and Augmented Recurrent Neural Networks](http://distill.pub/2016/augmented-rnns/)

[Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)

[Mastering the game of Go with deep neural networks and tree search](https://gogameguru.com/i/2016/03/deepmind-mastering-go.pdf)


## Fun Extra Credit Reading

#### Highway Networks, Speech Recognition
[Highway Networks (useful for understanding Highway LSTMs)](https://arxiv.org/pdf/1505.00387.pdf)

[Highway Long Short-Term Memory RNNs for Distant Speech Recognition](https://arxiv.org/abs/1510.08983)

[Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks](http://dl.acm.org/citation.cfm?id=1143891)

[The Rabiner HMM tutorial](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=18626)

####  Image Net and Descendents
[The Imagenet Data](http://imagenet.stanford.edu/)

[ImageNet Classification with Deep Convolutional Neural Networks](http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf)

[What I learned from Competing against Convnet on Imagenet](http://karpathy.github.io/2014/09/02/what-i-learned-from-competing-against-a-convnet-on-imagenet/)


[A guide to convolution arithmetic for deep learning](https://arxiv.org/pdf/1603.07285.pdf)

[Deconvolution and Checkerboard Artifacts](http://distill.pub/2016/deconv-checkerboard/)

[Rich feature hierarchies for accurate object detection and semantic segmentation](https://arxiv.org/pdf/1311.2524v5.pdf)

[Selective Search for Object Recognition](https://www.koen.me/research/pub/uijlings-ijcv2013-draft.pdf)
#### Using Deepnets as intuition for search directions
[DeepMath - Deep Sequence Models for Premise Selection](https://arxiv.org/pdf/1606.04442.pdf)

#### Recursive Cortical Networks (better than Deep Nets??)
[A generative vision model that trains with high data efficiency and breaks text-based CAPTCHAs](http://science.sciencemag.org/content/early/2017/10/26/science.aag2612.full)

#### Shrinking Networks: Teacher-student networks
[Do Deep Nets Really Need to be Deep?](http://papers.nips.cc/paper/5484-on-the-relations-of-lfps-neural-spike-trains.pdf)

#### Removing Recursion
[Feedforward Sequential Memory Networks: A New Structure to Learn Long-term Dependency](https://arxiv.org/abs/1512.08301)

[Quasi Recurrent  Neural Networks](https://arxiv.org/abs/1611.01576)

#### Cross-modal learning
[Cross Modal Distillation for Supervision Transfer](https://arxiv.org/abs/1507.00448)


#### External memory
[Neural Turing Machines](https://arxiv.org/pdf/1410.5401.pdf)

#### Audio Source Separation
[Deep clustering: Discriminative embeddings for segmentation and separation](http://ieeexplore.ieee.org/abstract/document/7471631/)

[DEEP ATTRACTOR NETWORK FOR SINGLE-MICROPHONE SPEAKER SEPARATION](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5805382/)

#### Audio scene labeling and source separation
[SoundNet: Learning Sound Representations from Unlabeled Video](https://projects.csail.mit.edu/soundnet/)

[UNSUPERVISED LEARNING OF SEMANTIC AUDIO REPRESENTATIONS](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46665.pdf)

[DEEP RANKING: TRIPLET MATCHNET FOR MUSIC METRIC LEARNING](http://www.ece.rochester.edu/projects/air/publications/lu2017deep.pdf)

[Unsupervised Cross-Modal Deep-Model Adaptation for Audio-Visual Re-Identification With Wearable Cameras](http://openaccess.thecvf.com/content_ICCV_2017_workshops/w8/html/Brutti_Unsupervised_Cross-Modal_Deep-Model_ICCV_2017_paper.html)

[Convolutional Recurrent Neural Networks for Polyphonic Sound Event Detection](https://arxiv.org/pdf/1702.06286.pdf)

#### Other stuff with sound

[Deep Cross-Modal Audio-Visual Generation](https://arxiv.org/abs/1704.08292)

#### Dialog Systems
[Building End-to-End Dialogue Systems Using Generative Hierarchical Neural Network Models](http://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11957/12160)

[Towards End-to-End Speech Recognition with Deep Convolutional Neural Networks](https://arxiv.org/abs/1701.02720)

[Dynamic Layer Normalization for Adaptive Neural Acoustic Modeling in Speech Recognition](https://arxiv.org/abs/1707.06065)

[Slides explaining what an iVector is](http://speech.cs.qc.cuny.edu/internal/talks/2015-01-23_AliRazaSyed_iVectors.pdf)

[Analysis of I-vector Length Normalization in Speaker Recognition Systems](https://pdfs.semanticscholar.org/1323/72db185b502e58765104c1465985fcab053a.pdf)

[Highway Networks (useful for understanding Highway LSTMs)](https://arxiv.org/pdf/1505.00387.pdf)

[Highway Long Short-Term Memory RNNs for Distant  Recognition](https://arxiv.org/abs/1510.08983)

[Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks](http://dl.acm.org/citation.cfm?id=1143891)

[The Rabiner HMM tutorial](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=18626)


#### Speech and Generation Systems

[WaveNet: A Generative Model for Raw Audio](https://deepmind.com/blog/wavenet-generative-model-raw-audio/)

[Deep Voice: Real-time Neural Text-to-Speech](https://arxiv.org/pdf/1702.07825.pdf)

[The Deep Voice Talk at ICML](https://vimeo.com/240608423)

[SampleRNN: Bengio's take on generating speech](https://arxiv.org/pdf/1612.07837.pdf)

[Tacotron is the speech generation system used at Google](https://ai.google/research/pubs/pub46150)

[Tacotron 2 is the 2018 speech generation system from Google](https://arxiv.org/abs/1712.05884)

[Check out Lyrebird](https://lyrebird.ai/)

#### Image generation
[Pixel Recurrent Neural Networks (WaveNet is based on this)](https://arxiv.org/abs/1601.06759)

[Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593)

[Conditional Image Generation with PixelCNN Decoders](https://arxiv.org/abs/1606.05328)

#### Estimating Confidence
[Learning Confidence for Out-of-Distribution Detection in Neural Networks](https://arxiv.org/abs/1802.04865)

[TRAINING CONFIDENCE-CALIBRATED CLASSIFIERS FOR DETECTING OUT-OF-DISTRIBUTION SAMPLES](https://openreview.net/pdf?id=ryiAv2xAZ)

[The Reddit discussion on the current state of the art in estimating confidence](https://www.reddit.com/r/MachineLearning/comments/907p7a/d_what_is_the_current_state_of_the_art_in/)

#### Why aren't deep nets overfitting?
[Understanding deep learning requires rethinking generalization](https://arxiv.org/abs/1611.03530)

[The Implicit Bias of Gradient Descent on Separable Data](http://www.jmlr.org/papers/volume19/18-188/18-188.pdf)