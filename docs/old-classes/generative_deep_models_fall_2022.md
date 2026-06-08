<a name="top"></a>

# DEEP GENERATIVE MODELS CS 496 FALL 2022

|[**Top**](#top)|  [**Calendar**](#calendar)| [**Slides**](#slides)|  [**Readings**](#readings)|

#### Loctation
Tech L160
#### Class Day/Time
MON WED FRI 1pm Central time
#### Office Hours
By appointment
#### Instructor
[Bryan Pardo](http://bryanpardo.com)

## Course Description 
Deep learning is a branch of machine learning based on algorithms that try to model high-level abstract representations of data by using multiple processing layers with complex structures. One of the most exciting areas of research in deep learning is that of generative models. Today’s generative models create text documents, write songs, make paintings and videos, and generate speech. This course is dedicated to understanding the inner workings of the technologies that underlie these advances. Students will learn about key methodologies, including Variational Autoencoders (VAEs), Generative Adversarial Networks (GANs), and Transformer-based language models.  This is an advanced course that presumes a good working understanding of traditional supervised neural network technology and techniques (e.g. convolutional networks, LSTMs, loss functions, regularization, gradient descent). 

Registration is by instructor permission only. This course is designed for doctoral students. Appropriately prepared BS and MS students may also be admitted, once doctoral student demand has been met.
  
<a name="calendar"></a>
## Course Calendar
[**Back to top**](#top)


| Week|   Day and Date| Topic                                                                                                                                          |Presenter        |Commentators           |
|----:|---------------|------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|-----------------------|
|1    | Wed Sept 21   | Course overview                                                                                                                                | Pardo           |                       |
|1    | Fri Sept 23   | [Autoregressive language models](https://interactiveaudiolab.github.io/course-deep-learning/slides/DL_attention_networks.pdf)                  | Pardo           |                       |
|2    | Mon Sept 26   | [Attention](https://interactiveaudiolab.github.io/course-deep-learning/slides/DL_attention_networks.pdf)                                       | Pardo           |                       | 
|2    | Wed Sept 28   | Embeddings: [The Illustrated Word2Vec](https://jalammar.github.io/illustrated-word2vec/)                                                       | Pardo           |                       | 
|2    | Fri Sept 30   | Transformers: [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)                                                | Pardo           |                       | 
|3    | Mon Oct 3     | Positional Encoding                                                                                                                            | Pardo           |                       | 
|3    | Wed Oct 5     | [Music Transformer](https://magenta.tensorflow.org/music-transformer)                                                                          | Julia B.        | Keshav & Clarissa     |
|3    | Fri Oct 7     | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf)                       | Mowafak A.      | Preetham & Keshav     | 
|4    | Mon Oct 10    | [GPT-3:Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)                                                                | Yujia & Ruth    | Isaiah & Julia        | 
|4    | Wed Oct 12    | [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)                                                     | Isaiah J.       | Aleksandr & Julia     | 
|4    | Fri Oct 14    | [Image GPT](https://openai.com/blog/image-gpt/)                                                                                                | Soroush S.      | Aneryben, Cameron & Amil | 
|5    | Mon Oct 17    | [Reformer: The Efficient Transformer](https://arxiv.org/abs/2001.04451)                                                                        | Tonmoay D.      | Shubhanshi & Caden & TC|        
|5    | Wed Oct 19    | Final projects & basics of stats/probability                                                                                                   | Pardo           |                       |
|5    | Fri Oct 21    | [Variational Inference, a Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf)                                                      | Pardo           |                       |
|6    | Mon Oct 24    | [Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908)                                                            | Pardo           | Preetham & Srik & Mowafak | 
|6    | Wed Oct 26    | [VQ-VAE: Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937)                                                            | Aneryben P.     | TC & Clarissa         |
|6    | Fri Oct 28    | [Beta-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework ](https://openreview.net/forum?id=Sy2fzU9gl)                | Srik G.         | James                 |
|7    | Mon Oct 31    | [DALL-E: Zero-Shot Text-to-Image Generation](https://proceedings.mlr.press/v139/ramesh21a.html)                                                | Liquian M.      | Jipeng & Mowafak      | 
|7    | Wed Nov 2     | [Jukebox: A Neural Net that Generates Music](https://openai.com/blog/jukebox/)                                                                 | Preetham P.     | Aleksandr & James     |
|7    | Fri Nov 4     | Generative Adversarial Networks                                                                                                                | Pardo           |                       |
|8    | Mon Nov 7     | [DCGAN: Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)        | Clarissa C.     | Aneryben, Conner & Omar|
|8    | Wed Nov 9     | [PROGRESSIVE GROWING OF GANS FOR IMPROVED QUALITY, STABILITY, AND VARIATION](https://arxiv.org/pdf/1710.10196.pdf)                             | TC L            | Yujia & Ruth  & Clarissa        |
|8    | Fri Nov 11    | [StyleGAN: A Style-Based Generator Architecture for Generative Adversarial Networks](https://github.com/NVlabs/stylegan)                       | Conner & Omar   | Shubhanshi & Caden  |  
|9    | Mon Nov 14    | [Cross-Modal Contrastive Learning for Text-to-Image Generation](https://arxiv.org/abs/2101.04702)                                              | James           | Amil & Cameron        |  
|9    | Wed  Nov 16   | [An Introduction to Diffusion Models](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/)                     | Shubhanshi & Caden | Srik, Conner & Omar|  
|9    | Fri Nov 18    | [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)                                      | Cameron & Amil | Yujia & Ruth           | 
|10   | Mon Nov 21    | [Guidance: a cheat code for diffusion models](https://benanne.github.io/2022/05/26/guidance.html)                                              | Pardo           | Liqian & Isaiah       |  
|10   | Wed Nov 23    | THANSKGIVING: No class                                                                                                                         |                 |                       | 
|10   | Fri Nov 25    | THANKSGIVING: No class                                                                                                                         |                 |                       | 
|11   | Mon Nov 28    | [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741)               | Jipeng S.       | Liqian & Tonmoay      |
|11   | Wed Nov 30    | [Google's Imagen](https://imagen.research.google/)                                                                                             | Aleksandr S.    | Jipeng & Soroush      | 
|11   | Fri Dec 2     | [DiffWave: A Versatile Diffusion Model for Audio Synthesis](https://arxiv.org/abs/2009.09761)                                                  | Keshav B.       | Tonmoay &Soroush               | 
|12   | Thu Dec 8     | Final project presentations 9AM-11AM                                                                                                           | EVERYONE!       | EVERYONE!             |


## Course assignments

### Reading: 40 points 
You will submit 20 reviews of readings from the course website. Each will be a single-page reaction to something you read from the links provided below.  

### Class Paper Presentation: 25 points
Once during the course of the term, you will be the lead person discussing the reading in class. This will mean you haven't just read the paper, but you've read related work, really understand it and can give a 30-minute presentation of the paper (including slides) and then lead a discussion about it.  
<ul>
<li>5 points: 1-on-1 meeting prior to the presentation, to go over slides and talking points</li>
<li>5 points: Initial slides at time of 1-on-1 meeting</li>
<li>10 points: Presenting topic & leading discussion </li>
<li>5 points: Updated slides </li>
</ul>

### Class Participation: 10 points
For two presentation OTHER than your own, you'll be expected to be 100% on top of the material and be the counterpoint to the presenter's point. I'll expect you to be making good points and display clear knowledge of the material.

### Project in generative modeling: 25 points
You will make, modify, and or analyze some work, project or subdomain in generative modeling. This may mean modifying MusicVAE or making a story generator on top of GPT-3. It may mean downloading an existing thing and experimenting with it or it may mean building a new thing. Duplicating a paper's results is always a great project. It could be a deep-dive literature review on a subtopic (a good first step towards writing a paper)... or something else, subject to approval of the proposal. The point breakdown for the project is as follows.  There will be a maximum of 10 projects in the class. Students are encouraged to pair up.

THis will be a group project. You will be in groups or 2 or 3. There will be no single projects.

<ul>
<li>5 points: Initial proposal</li>
<li>5 points: Progress report</li>
<li>15 points: Final presentation</li>
</ul>


<a name="slides"></a>
## Lecture Slides and Notebooks
[**Back to top**](#top)

### Lectures

<a name="readings"></a>
## Course Reading
[**Back to top**](#top)


### A BIG OVERVIEW OF GENERATIVE MODELING
1. [Deep Generative Modelling: A Comparative Review of VAEs, GANs, Normalizing Flows, Energy-Based and Autoregressive Models](https://arxiv.org/abs/2103.04922)

### AUTOREGRESSIVE MODELS 
1. [Pixel Recurrent Networks](http://proceedings.mlr.press/v48/oord16.html): A highly infulential autoregressive model for image generation

1. [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499): A highly infulential autoregressive model for audio generation


### TRANSFORMERS

#### Elements that lead up to Transformers
1. [The Illustrated Word2Vec](https://jalammar.github.io/illustrated-word2vec/): Transformers for text take word embeddings as input. So what's a word embedding? This is a walk through of one of the most famous embeddings 

1. [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) This is a good starting point blog on attention models, which is what Transformers are built on. 

1. [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf): This is the paper that the link above was trying to explain.

1. [Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078.pdf): This introduces encoder-decoder networks for translation. Attention models were first built on this framework. 

1. [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf): This paper introduces additive attention to an encoder-decoder. 

1. [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf): This paper introduces multiplicative attention, which is what Transformers use. 

1. [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385): This introduces the idea of "residual layers", which are layers that are skippable. This idea is used in Transformers.

#### The Transformer Architecture

1. [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/): A good initial walkthrough that helps a lot with understanding transformers  ** I'd start with this one to learn about transformers.**

1. [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html): An annotated walk-through of the "Attention is All You Need" paper, complete with detailed python implementation of a transformer.

1. [Attention is All You Need](https://arxiv.org/abs/1706.03762): The paper that introduced transformers, which are a popular and more complicated kind of attention network. 

#### Advanced Transformers 
1. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf): A widely-used language model based on Transformer encoder blocks.

1. [The Illustrated GPT-2](http://jalammar.github.io/illustrated-gpt2/): A good overview of GPT-2 and its relation to Transformer decoder blocks.

1. [GPT-3:Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)

1. [Image GPT](https://openai.com/blog/image-gpt/): Using a Transformer to make images. This isn't DALL-E, even though it's by OpenAI.

1. [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/pdf/2103.00020.pdf): This describes how DALL-E selects which of the many images it generates should be shown to the user.

1. [Perceiver: General Perception with Iterative Attention](https://arxiv.org/abs/2103.03206):  a model that builds upon Transformers that  scales to many more inputs. Not *exactly* about generation

1. [Self-attention with relative position representations](https://aclanthology.org/N18-2074/): This is what got relative positional encoding started.

1. [Reformer: The Efficient Transformer](https://arxiv.org/abs/2001.04451): This uses locality sensitive hashing to make attention much more efficient, moving it from taking O(n^2) and making it O(nlogn). This is a better paper to read than the "Transformers are RNNs" paper (below), in that it is much clearer with its math and ideas.

1. [Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention](https://proceedings.mlr.press/v119/katharopoulos20a.html): This paper talks about how to take the O(n^2) cost of attention and make it O(n)


1. [Relative Positional Encoding for Transformers with Linear Complexity](http://proceedings.mlr.press/v139/liutkus21a/liutkus21a.pdf): Positional encoding is messed up by the linear attention attention approach from "Transformers are RNNs". This paper addresses that problem.

1. [Zero-Shot Text-to-Image Generation](https://proceedings.mlr.press/v139/ramesh21a.html): This is the original version of DALL-E, which generates images conditioned on text captions. It is based on Transformer architecture.


1. [Music Transformer](https://magenta.tensorflow.org/music-transformer): Applying Transformers to music composition. 

#### Critiques of Transformers & Large Language Models
1. [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](http://faculty.washington.edu/ebender/papers/Stochastic_Parrots.pdf): This is the paper that Timnit Gebru and Margaret Mitchell got fired for publishing.

1. [Alignment of Language Agents](https://arxiv.org/abs/2103.14659): This is Deep Mind's critique of their own approach.

1. [Extracting Training Data from Large Language Models](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting): Did GPT-2 memorize a Harry Potter book? Read this and find out.

1. [Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646): Systematic experiments on how model size, prompt length, and frequency of an example in the training set impact our ability to extract memorized content.


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

1. [Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908): This is a walk-through of the math of VAEs. I think you should maybe start with this one.1. [Variational Inference, a Review for Statisticians](https://arxiv.org/pdf/1601.00670.pdf): This explains the math behind variational inference. One of the authors is an inventor of variational inference.

1. [An introduction to variational autoencoders](https://arxiv.org/pdf/1906.02691.pdf): This is by the inventors of the VAE.

1. [Tutorial: Deriving the Standard Variational Autoencoder (VAE) Loss Function](): This is the only paper I've found that walks you through all the details to derive the actual loss function.

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

1. [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.github.io/blog/2021/score/#connection-to-diffusion-models-and-others): This is a blog that explains how score-based models are also basically diffusion models.

1. [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)

1. [An Introduction to Diffusion Models](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/): A nice tutorial blog that has Pytorch code.

#### Advanced Difussion and Score Models

1. [Guidance: a cheat code for diffusion models](https://benanne.github.io/2022/05/26/guidance.html): if you want to understand DALL-E-2 and Imagen, you need to understand this.

1. [DiffWave: A Versatile Diffusion Model for Audio Synthesis](https://arxiv.org/abs/2009.09761): A neural vocoder done with diffusion from 2021

1. [Universal Speech Enhancement With Score-based Diffusion](https://serrjoa.github.io/projects/universe/)

1. [Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise](https://arxiv.org/abs/2208.09392): Do we need to add noise at each step or would any transform do?

##### Imagen

1. [High Fidelity Image Generation Using Diffusion Models](https://ai.googleblog.com/2021/07/high-fidelity-image-generation-using.html): A Google Blog that gives the chain of development that led to Imagen.

1. [Google's Imagen](https://imagen.research.google/): This is the Pepsi to DALL-E-2's Coke. 

##### DALL-E-2

1. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741): This is the diffusion model used in DALL-E-2

1. [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020): The CLIP representation. This is used in DALL-E-2.

1. [Hierarchical Text-Conditional Image Generation with CLIP Latents](https://arxiv.org/pdf/2204.06125.pdf): The DALL-E-2 paper. 

### TOPICS NOT COVERD IN CLASS (BUT THAT ARE WORTH LEARNING ABOUT)

#### Normalizing Flows
1. [Variational Inference with Normalizing Flows](http://proceedings.mlr.press/v37/rezende15.html): A differentiable method to take a simple distribution and make it arbitrarily complex. Useful for modeling distributions in deep nets. Can be added to VAEs.  These are being replaced by diffusion models.

#### FILM Layers
1. [FiLM: Visual Reasoning with a General Conditioning Layer](https://www.researchgate.net/publication/320014293_FiLM_Visual_Reasoning_with_a_General_Conditioning_Layer): Affine transformation of input layers that proves helpful in many contextx. Here's [the TL;DR version](https://ml-retrospectives.github.io/neurips2019/accepted_retrospectives/2019/film/). I'd start with the TL;DR.

#### Structured State Space Models
1. [Efficiently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2111.00396)

1. [The Annotated S4](https://srush.github.io/annotated-s4/): This is a guided walk through (with code) of a structured state space model.

1. [It's Raw! Audio Generation with State-Space Models](https://arxiv.org/pdf/2202.09729.pdf)

### Late-breaking, since December 2022 


1. [Competition-level code generation with AlphaCode](https://www.science.org/doi/10.1126/science.abq1158): This beats 1/2 of all human entrants into a coding competition.

1. [ChatGPT](https://openai.com/blog/chatgpt/): Already perhaps the most famous chatbot and most famous language model and it has been out about 2 weeks as of this writing.

1. [Riffusion](https://www.riffusion.com/about): Repurposes StableDiffusion to generate spectrograms. Cool opensource project. They should have published this, too. 

1. [Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models](https://arxiv.org/pdf/2212.03860.pdf): Just what it sounds like.

1. [Stable Attribution](https://www.stableattribution.com/) is a project that seeks to identify which training data images contributed to an image generated by the [Stable Diffusion](https://stablediffusionweb.com/) generative model.

1. [MusicLM: Generating Music From Text](https://google-research.github.io/seanet/musiclm/examples/): A model generating music audio from text descriptions such as "a calming violin melody backed by a distorted guitar riff".
