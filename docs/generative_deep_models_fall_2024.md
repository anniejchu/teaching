<a name="top"></a>

# DEEP GENERATIVE MODELS CS 496 FALL 2024

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Slides**](#slides)|  [**Readings**](#readings)| 

#### Location
Tech L168

#### Class Day/Time
Wed 2pm - 5pm

#### Instructor
[Bryan Pardo](http://bryanpardo.com)
Office hours by appointment


## Course Description

WARNING: This course is about reading papers. A lot of papers. If you don't want to read and discuss papers, this is not the course for you.

DESCRIPTION: One of the most exciting areas of research in deep learning is that of generative models. This course is dedicated to understanding the inner workings of the technologies that underlie these advances. Students will primarily learn about how Transformers, Variational Autoencoders, Reinforcement Learning and Diffusion Models are used to create text documents, write code, create music, images, speech, and more. We'll also look at legal and ethical implications of these models.  This is an advanced course that presumes a good working understanding of traditional supervised neural network technology and techniques (e.g. convolutional networks, LSTMs, loss functions, regularization, gradient descent). 

PREREQUISITES: Course admission is by permission of instructor. The best Northwestern course to prepare for this class is CS 449 Deep Learning, although being a doctoral student in CS will likely get you in, even if you haven't taken CS 449. 
  
<a name="calendar"></a>
## Course Calendar
[**Back to top**](#top)


| Week|   Day and Date| Topic                                                                                                                                           |Presenter        |Commentators            |
|----:|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|------------------------|
|     | Wed Sep 25    | Basics of Transformers: Attention, Embeddings,                                                                                                  | Pardo           | - |
|     |               | Basics of Transformers: Positional Encoding, Autoregression                                                                                     | Pardo           | - |
|     | Wed Oct 2     | Basics of Transformers, continued.                                                                                                              | Pardo           | - |
|     |               | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf)                        | Pardo           | - |
|     |               | At the end of class, watch this video [Should melodies be copyrightable?](http://allthemusic.info)                                              | Pardo           | - |
|     | Wed Oct 9     | [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)                                                      | Andrew Shen     | Gourav,Yoshii |
|     |               | [Allocating Ownership Rights in Computer Generated Works](https://www.law.berkeley.edu/wp-content/uploads/2024/01/Pam-Samuelson-Allocating-Ownership-Rights-in-Computer-Generated-Works.pdf)| Aidan Fitzsimons | Cesar |
|     |               | Class discussion about creativity/ownership                                                                                                     | -               | - |
|     | Wed Oct 16    | [The Curious Case of Neural Text Degeneration](https://arxiv.org/abs/1904.09751)                                                                | Vispi Karkaria  | Yiqi, Cesar |	
|     |               | [A Watermark for Large Language Models](https://arxiv.org/pdf/2301.10226.pdf)                                                                   | Ryan Chu        | Keyi, Aidan |
|     |               | Basics of Deep Reinforcement Learning + [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/)               | Pardo           | - |
|     | Wed Oct 23    | [Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741)                                                          | Yiqi Lyu        | Aidan, Zihan |
|     |               | [Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155.pdf)                                     | Keyi Wang       | Andrew, Monica |
|     |               | Basics of Variational Auto Encoders                                                                                                             | Pardo           | - |
|     | Wed Oct 30    | [VQ-VAE: Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937)                                                             | Cesar Ades      | Phillip, Jiaqi |
|     |               | [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)                                  | Zihan Guo       | Jiaqi |
|     |               | [Zero-Shot Text-to-Image Generation](https://arxiv.org/pdf/2102.12092.pdf)                                                                      | monica dou      | Nathan, Zihan|
|     | Wed Nov 6     | [LORA: Low-rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685.pdf)                                                      | Gourav Kumbhojkar | Andrew, Keyi |
|     |               | [MaskGIT: Masked Generative Image Transformer](https://openaccess.thecvf.com/content/CVPR2022/html/Chang_MaskGIT_Masked_Generative_Image_Transformer_CVPR_2022_paper.html)  | Pardo | Nathan, Yoshii |
|     |               | Basics of Diffusion/Score models                                                                                                                | Pardo           |   |
|     | Wed Nov 13    | No class: read some papers!                                                                                                                     |                 |   |
|     | Wed Nov 20    | [Vampnet: Music Generation via Masked Acoustic Token Modeling](https://arxiv.org/abs/2307.04686)                                                | Pardo      | Vispi, Patrick |
|     |               | [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/pdf/2112.10752)                                                | Jiaqi Guo       | Ryan |
|     | Wed Nov 27    | [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)                                       | Patrick Koller  | Gourav, Vispi |
|     |               | [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741)                | Yoshii Ma       | Phillip, Monica |
|     | Wed Dec 4     | [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/pdf/2204.06125.pdf)                                        | Abhishek Srivastava | Patrick, Yiqi |
|     |               | [Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188)                                                              | Nathan Pruyne   | Abhishek, Ryan |
|     |               | [Scalable Diffusion Models with Transformers](https://openaccess.thecvf.com/content/ICCV2023/html/Peebles_Scalable_Diffusion_Models_with_Transformers_ICCV_2023_paper.html)  | Philipp Srivastava  | Abhishek |
|     | Fri Dec 13    | Final Exam 9am - 11am: 5-minute one-on-one quiz on a randomly-selected paper you wrote a review of |

## Course assignments

### Reading: 40 points 
You will submit 20 one-page reviews of readings from the course website. 15 of these must be papers (not lecture slides, actual papers) scheduled for presenation in the course calendar. 5 of these can be chosen from the full set of readings for the course. Note...even though this class is about generative models, use of a generative model is not allowed in writing these up. The point is to communicate your own thoughts on the page. 

### Class Paper Presentation: 40 points
Once during the course of the term, you (and your partner) will be the lead in discussing the reading in class. This will mean you haven't just read the paper, but you've read related work, really understand it and can give a 30-minute (maximum) presentation of the paperand then lead a discussion about it.
Note, you are not allowed to go over 30 minutes in your presentation. Keeping to the time limit is part of the grade.

<ul>
<li>10 points: 1-on-1 meeting prior to the presentation, to go over slides and talking points</li>
<li>10 points: Initial slides at time of 1-on-1 meeting</li>
<li>15 points: Presenting topic (30 minutes) with updated slides & leading discussion (15 minutes)  </li>
<li>5  points:  Final submitted slides, updated in response to feedback from presentation </li>
</ul>

### Class Participation 10 points
For 2 papers that are presented in class (not your own), you are expected to be in class, on time, and really up on the material. I will feel free to call on you repeatedly and expect you to be engaged and give informed, thoughtful answers. Don't expect full points for this if you give brief or uninformed answers. You will be able to sign up for these papers at the start of the term. 

### Final Exam 10 points
Your final exam is this: I will select a paper that you did a review of and you'll spend 5 minutes talking about it, answering my questions as you go. If I believe you really read and understood the paper, full points. 


<a name="slides"></a>
## Lecture Slides and Notebooks

1. [Language Models](/generative_deep_models/0_RNNs_as_Langauge_Models.pdf)

1. [Attention Networks](/generative_deep_models/1_attention_networks.pdf)

1. [Embeddings](/generative_deep_models/2_embeddings.pdf)

1. [Positional Encoding, Attention and Embeddings Notebook](/generative_deep_models/Embeddings_Positional_Encoding_Attention.ipynb)

1. [Transformers](/generative_deep_models/3_transformers.pdf)

1. [Deep Reinforcement Learning: Q Learning](/generative_deep_models/4_deep_RL_1_Q_learning.pdf)

1. [Deep Reinforcement Learning: Policy Gradients](/generative_deep_models/5_deep_RL_2_policy_gradients.pdf)

1. [Deep Reinforcement Learning: Human Feedback](/generative_deep_models/6_deep_RL_3_human_feedback.pdf)

1. [Variational Inference](/generative_deep_models/7_variational_inference.pdf)

1. [Variational Autoencoders](/generative_deep_models/8_variational_autoencoders.pdf)

1. [Generative Adversarial Networks](/generative_deep_models/9_GANs.pdf)

1. [Diffusion/Score Models](/generative_deep_models/10_GM_Score-Diffusion_Models.pdf)

1. [Measures of Image Quality](/generative_deep_models/11_GM_measuring_image_quality.pdf)

[**Back to top**](#top)

### Lectures

<a name="readings"></a>
## Course Reading
[**Back to top**](#top)



### INFLUENTIAL AUTOREGRESSIVE MODELS 
1. [Pixel Recurrent Networks](http://proceedings.mlr.press/v48/oord16.html): A highly infulential autoregressive model for image generation

1. [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499): A highly infulential autoregressive model for audio generation


### TRANSFORMERS & LANGUAGE MODELS

#### Architectural elements that lead up to Transformers

1. [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) This is a good starting point blog on attention models, which is what Transformers are built on. 

1. [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf): This is the paper that the link above was trying to explain.

1. [Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078.pdf): This introduces encoder-decoder networks for translation. Attention models were first built on this framework. 

1. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf): This paper introduces additive attention to an encoder-decoder. 

1. [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf): This paper introduces multiplicative attention, which is what Transformers use. 

1. [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385): This introduces the idea of "residual layers", which are layers that are skippable. This idea is used in Transformers.

#### Embeddings 

1. [The Illustrated Word2Vec](https://jalammar.github.io/illustrated-word2vec/): Transformers for text take word embeddings as input. So what's a word embedding? This is a walk through word embeddings, at a high level, with no math.

1. [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf): This is the Word2Vec paper.

1. [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/): The paper that describes the Glove embedding, which is an improvement on Word2Vec, and has downloadable embeddings to try. There is math here.

1. [Using the Output Embedding to Improve Language Models](https://arxiv.org/abs/1608.05859): In transformers, they actually learn their embeddings at the same time as everything else and tie the input embedding to the output embedding. This paper explains why.

#### The Transformer Architecture

1. [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/): A good initial walkthrough that helps a lot with understanding transformers  ** I'd start with this one to learn about transformers.**

1. [The Annotated Transformer](http://nlp.seas.harvard.edu/annotated-transformer/): An annotated walk-through of the "Attention is All You Need" paper, complete with detailed python implementation of a transformer. ** If you actually want to understand transformer implementation, you should read this in depth...and play with the code.**

1. [Attention is All You Need](https://arxiv.org/abs/1706.03762): The paper that introduced transformers, which are a popular and more complicated kind of attention network. 

#### About positional encoding

1. [Self-Attention with Relative Position Representations](https://arxiv.org/abs/1803.02155): The most frequently used alternative to absolute positional encoding

1. [Rotary Positional Encoding](https://paperswithcode.com/method/rope#:~:text=Rotary%20Position%20Embedding%2C%20or%20RoPE,dependency%20in%20self%2Dattention%20formulation.): claims to combine the benefits of both absolute and relative positional encoding 

1. [What Do Position Embeddings Learn? An Empirical Study of Pre-Trained Language Model Positional Encoding](https://arxiv.org/pdf/2010.04903): Why not learn your positional encoding? What happens if you do that?

#### BERT and GPT, two foundational architectures 

1. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf): A widely-used language model based on Transformer encoder blocks.

1. [The Illustrated GPT-2](http://jalammar.github.io/illustrated-gpt2/): A good overview of GPT-2 and its relation to Transformer decoder blocks.

1. [GPT-3:Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): This explores the range of things that you can do with a GPT model.

#### Why sampling strategies matter

1. [The Curious Case of Neural Text Degeneration](https://arxiv.org/abs/1904.09751): When you sample from the output of a language model, it matters a LOT just how you sample. Read this to understand why. 

1. [A Watermark for Large Language Models](https://arxiv.org/pdf/2301.10226.pdf): Can you use a sampling strategy to watermark generated text?


#### Symbolic Music Making with Transformers

1. [Music Transformer](https://magenta.tensorflow.org/music-transformer): Applying Transformers to music composition. 

1. [Anticipatory Music Transformer: A Controllable Infilling Model for Music](https://crfm.stanford.edu/2023/06/16/anticipatory-music-transformer.html)


#### Making Images with Transformers

1. [Image GPT](https://openai.com/blog/image-gpt/): Using a Transformer to make images. This isn't DALL-E, even though it's by OpenAI.

1. [Zero-Shot Text-to-Image Generation](https://arxiv.org/pdf/2102.12092.pdf): This is the original version of DALL-E, which generates images conditioned on text captions. It is based on Transformer architecture.

1. [MaskGIT: Masked Generative Image Transformer](https://openaccess.thecvf.com/content/CVPR2022/html/Chang_MaskGIT_Masked_Generative_Image_Transformer_CVPR_2022_paper.html)  This lets you generate in PARALLEL, not auto-regressively

1. [MaskBit: Embedding-free Image Generation via Bit Tokens](https://weber-mark.github.io/projects/maskbit.html): A 2024-SOTA image generator based on MaskGiT 


#### Making Transformers Efficient by Making Attention Efficient

1. [Reformer: The Efficient Transformer](https://arxiv.org/abs/2001.04451): This uses locality sensitive hashing to make attention much more efficient, moving it from taking O(n^2) and making it O(nlogn). 

1. [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135): This is a VERY popular paper and lots of people use this approach

#### Adding Memory/Scratch Space to a Transformer

1. [Memory Transformer](https://arxiv.org/abs/2006.11527)

1. [Vision Transformers Need Registers](https://arxiv.org/abs/2309.16588)

1. [Think before you speak: Training Language Models With Pause Tokens](https://arxiv.org/abs/2310.02226)

1. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf)

#### How to tokenize audio to allow language modeling of sound

1. [WAV2VEC: UNSUPERVISED PRE-TRAINING FOR SPEECH RECOGNITION](https://arxiv.org/pdf/1904.05862.pdf): This describes a way to build a dictionary of audio tokens that is used in MusicLM

1. [Wav2vec 2.0: Learning the structure of speech from raw audio](https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/): The 2nd iteration of wav2vec

1. [SoundStream: An End-to-End Neural Audio Codec](https://arxiv.org/pdf/2107.03312.pdf): Perhaps the top (as of 2023) audio codec. It is used in multiple audio langague models to tokenize the audio for the language model.

1. [High-Fidelity Audio Compression with Improved RVQGAN](https://arxiv.org/pdf/2306.06546): This is SOTA for audio encoders, as of July 2024

#### Using language models on audio tokens

1. [W2v-BERT: Combining Contrastive Learning and Masked Language Modeling for Self-Supervised Speech Pre-Training](https://arxiv.org/abs/2108.06209): Masked inference language model method to learn audio tokens. This is what is actually used in MusicLM

1. [AudioLM: A Language Modeling Approach to Audio Generation](https://google-research.github.io/seanet/audiolm/examples/): A language model for generating speech continuation

1. [MusicLM: Generating Music From Text](https://google-research.github.io/seanet/musiclm/examples/): A model generating music audio from text descriptions such as "a calming violin melody backed by a distorted guitar riff".

1. [Vampnet: Music Generation via Masked Acoustic Token Modeling](https://arxiv.org/abs/2307.04686): Generating non-autoregressively, similar to MaskGit

#### Fine tuning of langauge models

1. [LORA: Low-rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685.pdf): Microsoft's approach to fast, efficient retraining for downstream tasks.


### Reinforcement learning for Model Alignment 

1. [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html): This is an entire book, but it is the one I learned RL from. 

1. [Policy Gradient Methods: Tutorial and New Frontiers](https://youtu.be/y4ci8whvS1E?t=2230): This is a video lecture that explains reinforcement learning policy grading methods. This is underlying tech used for training ChatGPT. Yes, this video is worth a "reading" credit. Yes, I started it 37 minutes into the lecture on purpose. You don't have to watch the first half of the lecture.

1. [Andrew K.s blog on Deep Reinforcement Learning](http://karpathy.github.io/2016/05/31/rl/): When combined with the video tutorial above, you'll more-or-less understand policy gradient methods for deep reinforcement learning

1. [Proximal Policy Optimization Algorithms](https://arxiv.org/pdf/1707.06347.pdf): The paper that (mostly) explains the RL approach used in InstructGPT (the precursor to ChatGPT)

1. [This blog on RL from human feedback](https://openai.com/research/learning-from-human-preferences): read the paper linked at the start of the blog. It teaches how to learn a reward function from human feedback, so you can do RL.

1. [This blog on Aligning language models to follow instructions](https://openai.com/research/instruction-following) together explain how ChatGPT is fine-tuned to do prompt answering by combining proximal policy optimization and RL from human feedback (the two previous papers on this list).

1. [ChatGPT](https://openai.com/blog/chatgpt/): Already perhaps the most famous chatbot and most famous language model and it has been out about 2 weeks as of this writing.

#### Moving beyond RL for Model Alignment

1. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290):  DPO directly optimizes for the policy best satisfying human preferences with a simple classification objectiv. No RL required!

1. [KTO: Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/pdf/2402.01306): Directly maximizes the utility of generations instead of maximizing the log-likelihood of preferences. Maybe better than DPO?

### Multimodal Langauge Modeling

1. [GPT-4 with vision (GPT-4V)](https://openai.com/research/gpt-4v-system-card): enables users to instruct GPT-4 to analyze image inputs provided by the user, and is the latest capability we are making broadly available

1. [LLaVA: Large Language and Vision Assistant](https://llava-vl.github.io):a large multimodal model that combines a vision encoder and Vicuna for general-purpose visual and language understanding

1. [LLark: A Multimodal Foundation Model for Music](https://arxiv.org/abs/2310.07160): Mix Jukebox and Llama 2 and you get this.


### Making Language Models Safe

1. [The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions](https://arxiv.org/pdf/2404.13208)

### GENERATIVE ADVERSARIAL NETWORKS (GANS)

#### Creating adversarial examples
1. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) : This paper got the ball rolling by pointing out how to make images that look good but are consistently misclassified by trained deepnets.

####  Creating GANs

1. [Generative Adversarial Nets](https://arxiv.org/pdf/1406.2661v1.pdf): The paper that introduced GANs

1. [2016 Tutorial on Generative Adversarial Networks](https://arxiv.org/pdf/1701.00160.pdf) by one of the creators of the GAN. This one's long, but good.

1. [DCGAN: Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434): This is an end-to-end model. Many papers build on this.

#### Advanced GANS

1. [PROGRESSIVE GROWING OF GANS FOR IMPROVED QUALITY, STABILITY, AND VARIATION](https://arxiv.org/pdf/1710.10196.pdf) This is used in StyleGAN and was state-of-the-art in 2018.

1. [StyleGAN: A Style-Based Generator Architecture for Generative Adversarial Networks](https://github.com/NVlabs/stylegan): As of 2019, this was the current state-of-the-art for GAN-based image generation.

1. [StyleGAN2-ADA: Training Generative Adversarial Networks with Limited Data](https://github.com/NVlabs/stylegan2-ada-pytorch): : As of 2020, this was the current state-of-the-art for GAN-based image generation.

1. [Cross-Modal Contrastive Learning for Text-to-Image Generation](https://arxiv.org/abs/2101.04702) As of 2021, this was the best GAN for text-conditioned image generation. Note it's use of contrastive loss. You'll see that again in CLIP.

1. [Adversarial Audio Synthesis](https://arxiv.org/abs/1802.04208): introduces WaveGAN, a paper about applying GANs to unsupervised synthesis of raw-waveform audio.

1. [MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis](https://github.com/descriptinc/melgan-neurips): Doing speech synthesis with GANs.

1. [HiFi-GAN: Generative Adversarial Networks for Efficient and High Fidelity Speech Synthesis](https://proceedings.neurips.cc/paper/2020/hash/c5d736809766d46260d816d8dbc9eb44-Abstract.html): Even better speech synthesis with GANs.

### Variational Auto Encoders (VAEs)

#### Background needed for Variational Autoencoders

1. [The Deep Learning Book's Chapters on Probability and Linear Algebra](https://www.deeplearningbook.org). Read these before the Easy Intro to KL Divergence

1. [An Easy Introduction to Kullback-Leibler (KL) Divergence ](https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained). Read this before reading about ELBO 

1. [Jenson's Inequality (an example with code)](https://machinelearningmastery.com/a-gentle-introduction-to-jensens-inequality/). Read this before reading about ELBO

1. [Evidence Lower Bound, Clearly Explained](https://www.youtube.com/watch?v=IXsA5Rpp25w): A video walking through Evidence Lower Bound.

1. [A walkthrough of Evidence Lower Bound (ELBO)](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf): Lecture notes from David Blei, one of the inventors of ELBO. ELBO is what you optimize when you do variational inference in a VAE.

1. [Categorical Reparameterization with Gumbel-Softmax](https://arxiv.org/abs/1611.01144): This is a way of allowing categorical latent variables in your model so you can run a differentiable gradient descent algorithm through them. This is used in Vector-Quantized VAEs.

1. [Probabilistic Graphical Models](https://ermongroup.github.io/cs228-notes/): Lecture notes from the class taught at Stanford.


#### Autoencoders

1. [A starter blog on AutoEncoders and VAEs](https://towardsdatascience.com/generating-images-with-autoencoders-77fd3a8dd368): Probably a good place to start.

1. [The Deep Learning Book's Chapter on Autoencoders](https://www.deeplearningbook.org/contents/autoencoders.html)

1. [From neural PCA to deep unsupervised learning ](https://www.sciencedirect.com/science/article/pii/B9780128028063000087): This paper introduces Ladder networks, which will come back when we get to VAEs

#### BASIC Variational Auto Encoders (VAEs)

1. [Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908): This is a walk-through of the math of VAEs. I think you should maybe start with this one.

1. [Variational Inference, a Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf): This explains the math behind variational inference. One of the authors is an inventor of variational inference.

1. [An introduction to variational autoencoders](https://arxiv.org/pdf/1906.02691.pdf): This is by the inventors of the VAE.

1. [Tutorial: Deriving the Standard Variational Autoencoder (VAE) Loss Function](https://arxiv.org/abs/1907.08956): This is the only paper I've found that walks you through all the details to derive the actual loss function.

#### ADVANCED VAEs

1. [VQ-VAE: Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937)

1. [Conditional VAE: Learning Structured Output Representation using Deep Conditional Generative Models](http://www.cs.toronto.edu/~bonner/courses/2020s/csc2547/papers/generative/conditional-image-generation/conditional-vae,-sohn,-nips2015.pdf): Making a controllable VAE through conditioning

1. [Beta-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework ](https://openreview.net/forum?id=Sy2fzU9gl): This is about making disentangled representations: making the VAEs latent variables meaningful to us.

1. [Isolating Sources of Disentanglement in VAEs](https://arxiv.org/pdf/1802.04942.pdf): More on disentangled representations in VAEs

1. [Ladder VAEs](https://arxiv.org/abs/1602.02282): Hierarchical VAEs 

1. [Adversarial Auto-Encoders](https://arxiv.org/abs/1511.05644): You can guess what this is.

1. [A Wizard's Guide to Adversarial Autoencoders](https://towardsdatascience.com/a-wizards-guide-to-adversarial-autoencoders-part-1-autoencoder-d9a5f8795af4): This is a multi-part tutorial that will be helpfup for understanding AAEs.

1. [From Autoencoder to Beta-VAE](https://lilianweng.github.io/posts/2018-08-12-vae/): Lilian Weng's overview of most kinds of autoencoders

#### VAE Applications

1. [MUSIC VAE: Learning Latent Representations of Music to Generate Interactive Musical Palettes](http://ceur-ws.org/Vol-2068/milc7.pdf): Making controllable music composition with VAEs

1. [Jukebox: A Neural Net that Generates Music](https://openai.com/blog/jukebox/)....with a combination of autoencoders and GANs

1. [Accelerated antimicrobial discovery via deep generative models and molecular dynamics simulations](https://www.nature.com/articles/s41551-021-00689-x): Using a WAE to generate new drugs


### Diffusion and Score Models

1. [Deep unsupervised learning using nonequilibrium thermodynamics](http://proceedings.mlr.press/v37/sohl-dickstein15.html): The 2015 paper where diffusion models were introduced. 

1. [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239): This was a break-out paper from 2020 that got people excited about diffusion models.

1. [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion): This provides a step-by-step walkthrough of the Denoising Diffusion Probabilistic Models, but with pytorch code

1. [DIFFWAVE: A VERSATILE DIFFUSION MODEL FOR AUDIO SYNTHESIS](https://arxiv.org/pdf/2009.09761): A 2021 paper that made a splash in audio-synthesis

1. [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.github.io/blog/2021/score/#connection-to-diffusion-models-and-others): This is a blog that explains how score-based models are also basically diffusion models.

1. [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)

1. [An Introduction to Diffusion Models](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/): A nice tutorial blog that has Pytorch code.

#### Advanced Diffussion and Score Models

1. [DiffWave: A Versatile Diffusion Model for Audio Synthesis](https://arxiv.org/abs/2009.09761): A neural vocoder done with diffusion from 2021

1. [Universal Speech Enhancement With Score-based Diffusion](https://serrjoa.github.io/projects/universe/)

1. [Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise](https://arxiv.org/abs/2208.09392): Do we need to add noise at each step or would any transform do?


#### Latent Diffusion (as seen in Stability AI's image generator)

1. [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/pdf/2112.10752) : How to use an autoencoder to put images into a latent space so you can do diffusion with fewer resources

1. [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/): Stability AI made a great diffusuion model. Here's a high-level overview of how it works.

#### Combining Diffusion and Transformers

1. [Scalable Diffusion Models with Transformers](https://openaccess.thecvf.com/content/ICCV2023/html/Peebles_Scalable_Diffusion_Models_with_Transformers_ICCV_2023_paper.html): A 2023 paper that uses a Transformer architecture to do diffusion

1. [Long-form Music Generation with Latent Diffusion](https://arxiv.org/pdf/2404.10301): This is a 2024 paper that describes how to use DiT models to do music audio generation

1. [Stable Audio Open](https://arxiv.org/abs/2407.14358): A July 2024 paper that describes the architecture of Stability AI's open-source audio generation model


#### Making diffusion faster

1. [Progressive Distillation for fast sampling of Diffusion Models](https://arxiv.org/pdf/2202.00512): This 2022 ICLR paper introduces the v-prediction objective, which is a weighted sum of of x0 and eps (the two learning objectives typically used in diffusion)

1. [Consistency Trajectory Models](https://consistencytrajectorymodel.github.io/CTM/). For single-step diffusion model sampling, CTM offers diverse sampling options and balances computational budget with sample fidelity effectively.

#### Steerable diffusion (text conditioning)

1. [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/pdf/2105.05233.pdf): This paper describes many technical details used in the GLIDE paper...and therefore in DALL-E-2.  It introduces classifer guidance

1. [Classifier-free Diffusion Guidance](https://arxiv.org/abs/2207.12598): The 2021 paper that defined how we use text prompting w/o a classifier to guide diffusion. 

1. [Guidance: a cheat code for diffusion models](https://benanne.github.io/2022/05/26/guidance.html): if you want to understand DALL-E-2 and Imagen, you need to understand this. It's an easier-to-follow explanation of the Classifier-free Diffusion Guidance idea.

1. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741): This is paper that lays the groundwork for  DALL-E-2. 

1. [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020): The CLIP representation. This is used in DALL-E-2.

1. [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/pdf/2204.06125.pdf): The DALL-E-2 paper. 

1. [InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/pdf/2211.09800)

1. [DITTO:Diffusion Inference-Time T-Optimization for Music Generation](https://ditto-music.github.io/web/)

### Ethics and Societal Effects of Generative Modeling

1. [Pam Samuelson's AI Meets Copyright](https://www.youtube.com/watch?v=6sDGIrVO6mo). This is a video lecture on generative AI and copyright law from one of top copyright scholars in the USA.

1. [Allocating Ownership Rights in Computer Generated Works](https://www.law.berkeley.edu/wp-content/uploads/2024/01/Pam-Samuelson-Allocating-Ownership-Rights-in-Computer-Generated-Works.pdf)

1. [Sociotechnical Safety Evaluation of Generative AI Systems](https://arxiv.org/pdf/2310.11986.pdf): A big overview paper on how to ensure your generative AI is going to minimize possible harms.

1. [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf): This is the paper that Timnit Gebru and Margaret Mitchell got fired from Google's Ethical AI team for publishing.

1. [Alignment of Language Agents](https://arxiv.org/abs/2103.14659): This is Deep Mind's critique of their own approach.

1. [Open AI's analysis of GPT-4 potential harms](https://cdn.openai.com/papers/gpt-4-system-card.pdf): Worth a serious read

1. [The Ethical Implications of Generative Audio Models: A Systematic Literature Review](https://arxiv.org/pdf/2307.05527.pdf): By Northwestern's own Julia Barnett!

1. [Foregrounding Artist Opinions: A Survey Study on Transparency, Ownership, and Fairness in AI Generative Art](https://arxiv.org/pdf/2401.15497): What do artists think about GenerativeAI?

### How bad is the memorization problem in generative models?

1. [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646): Systematic experiments on how model size, prompt length, and frequency of an example in the training set impact our ability to extract memorized content.

1. [Extracting Training Data from Large Language Models](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting): Did GPT-2 memorize a Harry Potter book? Read this and find out.

1. [Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188): Exactly what it sounds like.

1. [Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models](https://arxiv.org/pdf/2212.03860.pdf): Just what it sounds like.


### TOPICS NOT COVERD IN CLASS (BUT THAT ARE WORTH LEARNING ABOUT)

#### Normalizing Flows
1. [Variational Inference with Normalizing Flows](http://proceedings.mlr.press/v37/rezende15.html): A differentiable method to take a simple distribution and make it arbitrarily complex. Useful for modeling distributions in deep nets. Can be added to VAEs. 

#### FILM Layers
1. [FiLM: Visual Reasoning with a General Conditioning Layer](https://www.researchgate.net/publication/320014293_FiLM_Visual_Reasoning_with_a_General_Conditioning_Layer): Affine transformation of input layers that proves helpful in many contextx. Here's [the TL;DR version](https://ml-retrospectives.github.io/neurips2019/accepted_retrospectives/2019/film/). I'd start with the TL;DR.

#### Structured State Space Models
1. [Efficiently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2111.00396)

1. [The Annotated S4](https://srush.github.io/annotated-s4/): This is a guided walk through (with code) of a structured state space model.

1. [It's Raw! Audio Generation with State-Space Models](https://arxiv.org/pdf/2202.09729.pdf)

1. [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752): Adds input-dependent "attention" (selectivity) to SSMs and claims to beat Transformers at their own game.




