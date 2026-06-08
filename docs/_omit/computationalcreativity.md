# COMPUTATIONAL CREATIVITY, Northwestern University EECS 397/497 fall 2019
## Loctation: Technological Institute LG52
## Day/Time: Thursdays, 1:00pm - 3:50pm
## Instructor: [Bryan Pardo](http://bryanpardo.com)
## Course Description
Computational creativity is a multidisciplinary field that lies at the intersection of artificial intelligence, cognitive psychology, philosophy, and the arts. The field is concerned with the theoretical and practical issues in the study of creativity. The goal of computational creativity is to achieve one of the following:

* To construct a program or computer capable of human-level creativity.

* To better understand creativity and to formulate an algorithmic perspective on creative behavior.

* To design programs that can enhance human creativity without necessarily being creative themselves.

In this course, students will read and discuss theoretical writings on the nature and proper definition of creativity. They will also read about and experiment with existing computational creativity systems (e.g. David Cope’s Experiments in Musical Intelligence and Google’s Project Magenta). In parallel, they will perform practical work implementing systems aimed at achieving one of the three goals listed above. 

## Course Calendar

|Week|Date      | Topic                                          | Due         |           
|---:|----------|------------------------------------------------|-------------|
|1   | Sep 26   | Basics of deep nets. Can computers create art? |     
|2   | Oct 3    | What is Creativity? Who owns creative works?   | 5 reviews
|3   | Oct 10   | Algorithmic music composition                  | 4 reviews
|4   | Oct 17   | Algorithmic music composition                  | 4 reviews
|5   | Oct 24   | No class: prepare your proposal                | 4 reviews
|6   | Oct 31   | Algorithmic image generation                   | initial proposal 
|7   | Nov 7    | Algorithmic image generation                   | Project plan
|8   | Nov 14   | Cross-modal generation                         | 4 reviews
|9   | Nov 21   | Text and story generation                      | 4 reviews
|10  | Nov 28   | No class: Thanksgiving                         | 
|11  | Dec 5    | Support rather than supplant?                  | project website
|12  | Dec 10 (9-11am) | Final project presentation              | final presentation

## Course assignments

### Reading: 50 points 
You will submit 25 reviews of readings/videos/music from the course website. Each will be a single-page reaction to something you read/watched/heard from the links provided below. Each review will be worth 2 points. Reviews are due on the schedule shown in the course calendar. 

### Class Paper Presentations: 10 points
Once during the course of the term, you will be the lead person discussing the reading in class. This will mean you haven't just read the paper, but you've read related work, really understand it and can give a brief presentation of the paper (including slides) and then lead a discussion about it. (10 points) 

### Class participation: 10 points
Each week (even weeks when you're not presenting) you are expected to show up, have read the papers and be able to discuss ideas. Every week you show up and substantially contribute to the discussion, you get 1 point. If you don't show up or you don't say anything that week, you don't get the point. 

### Project in computational creativity: 30 points
You will make, modify, and or analyze some work or project in computational creativity. This may mean modifying MusicVAE or making a simple story generator of your own. It may mean downloading an existing thing and experimenting with it or it may mean building a new thing. It may mean making a program that analyses creativity or a creativity aid...or something I haven't been able to come up with.  The point breakdown for the project is as follows
<ul>
<li>5 points: Initial proposal</li>
<li>5 points: Project plan</li>
<li>10 points: Project website</li>
<li>10 points: Final presentation</li>
</ul>

Recent student projects can be found [here](cc2019projects.md).

## Week 1 Basics of Deep Nets

### Basics of Deep Nets 
[Chapter 4 from Machine Learning](http://www.cs.northwestern.edu/~pardo/courses/eecs349/readings/chapter4-ml.pdf)

[Convolutional Networks for Images, Speech, and Time-Series](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.32.9297)


[Generative Adversarial Nets](http://papers.nips.cc/paper/5423-generative-adversarial-nets)

[Slides of the NeurIPS GAN tutorial](https://media.nips.cc/Conferences/2016/Slides/6202-Slides.pdf)

[Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

### Can Computers Create Art?
[On the Future of Computers and Creativity](http://www.doc.gold.ac.uk/~mas02md/wp-content/uploads/2014/09/CreativeComputing1.pdf)

[Can Computers Create Art?](https://www.mdpi.com/2076-0752/7/2/18/htm)

[The "Can Computers Create Art?" Talk on video](https://www.youtube.com/watch?v=V6ogUxTqAsA&amp=&t=3s)

### A Computer "Artist" 
[Deepfake Salvador Dalí takes selfies with museum visitors](https://www.theverge.com/2019/5/10/18540953/salvador-dali-lives-deepfake-museum)


## Week 2: What is Creativity? How do you measure it? Who owns creativce works?
 
### In Class Presentations
Max Morrison: What is KL Divergence?

Andong Li Zhao: [Approaches to Measuring Creativity: A Systematic Literature Review](https://www.researchgate.net/publication/322859368_Approaches_to_Measuring_Creativity_A_Systematic_Literature_Review)

Max Morrison: [Quantifying the Creativity Support of Digital Tools through the Creativity Support Index](https://www.researchgate.net/profile/Erin_Cherry/publication/262046838_Quantifying_the_Creativity_Support_of_Digital_Tools_through_the_Creativity_Support_Index/links/54a436530cf267bdb90673de/Quantifying-the-Creativity-Support-of-Digital-Tools-through-the-Creativity-Support-Index.pdf)

Brandon Harris: [Monkey Selfie Copyright Dispute](https://en.wikipedia.org/wiki/Monkey_selfie_copyright_dispute)

### Other readings...
#### What is Creativity?
[The Standard Definition of Creativity](https://www.tandfonline.com/doi/full/10.1080/10400419.2012.650092?casa_token=pUEInNMyp9MAAAAA:B0V2syv40DoLO_wYXE1j4ybePa6m40RFZ4TtCDs1Pfv3t-bnp3r7TTZHCL8rLtkT87oIKwxMk0Q)

#### How do we measure creativity?
[How Creativity is Measured](https://www.artsy.net/article/artsy-editorial-creativity-measured-difficult)

#### Who are the stakeholders in a creative work?
[Artificial Intelligence and Music: Open Questions of Copyright Law and Engineering Praxis](https://www.mdpi.com/2076-0752/8/3/115/htm)


## Week 3: Algorithmic music composition

### A talk you should go to
Come to Andrew McPherson's talk and react to that: 3rd floor lecture room, Mudd building. Noon, Oct 9.

### A Historical Perspective 
Andreas Bugler CHAPTER 4 [BOOK: Formalized Music Thought and Mathematics in Composition - Xenakis](https://monoskop.org/images/7/74/Xenakis_Iannis_Formalized_Music_Thought_and_Mathematics_in_Composition.pdf)  ** You can review up to 3 chapters of this book. Each chapter is worth 1 point.**

Connor Bain [David Cope and Experiements in Musical Intelligence](https://www.computerhistory.org/atchm/algorithmic-music-david-cope-and-emi/)

[David Cope's YouTube Channel](https://www.youtube.com/channel/UC2Ma0T4VZtmtB6kMmNw7QIA)

### "Deep" takes on music making

[A Universal Music Translation Network](https://arxiv.org/pdf/1805.07848.pdf)

[The output of Facebooks Universal Music Translation Network](https://thenextweb.com/artificial-intelligence/2018/05/22/facebook-made-an-ai-that-convincingly-turns-one-style-of-music-into-another/)

S [Dadabots](http://dadabots.com). This is a project where deep nets are generating entire albums of content. Note there are several papers an albums on this site. If a student presenter wants to pick one, I'm open to that. 

## Week 4: "Deep" algorithmic music composition

### Variational Auto Encoders (VAES)

[Autoencoders](http://ufldl.stanford.edu/tutorial/unsupervised/Autoencoders/)

Jacob Kelter [A tutorial on Variational Autoencoders](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/)

[Stretch reading goal: A more in depth tutorial on Variational Autoencoders (academic)](https://arxiv.org/abs/1606.05908)

[Learning Latent Representations of Music to Generate Interactive Musical Palettes](http://ceur-ws.org/Vol-2068/milc7.pdf) This is the MusicVAE paper.

[The MusicVAE blog description](https://magenta.tensorflow.org/music-vae)


### GAN music generation
[The ISMIR 2019 tutorial on generating music with GANs](https://salu133445.github.io/ismir2019tutorial/)

### Other deep methods

Alexander Fang [DeepBach: a Steerable Model for Bach Chorales Generation](https://arxiv.org/abs/1612.01010)

### Other Readings
[Deepfakes and Cheapfakes](https://datasociety.net/output/deepfakes-and-cheap-fakes/)

[Music Generation by Deep Learning - Challenges and Directions](https://arxiv.org/abs/1712.04371)

[Deep Learning Techniques for Music Generation -- A Survey](https://arxiv.org/abs/1709.01620)

### Creative Computation Systems

[Magenta](https://magenta.tensorflow.org)

[DeepBach Example Output & Code](https://sites.google.com/site/deepbachexamples/)


## Week 5: NO CLASS. Read papers. Write your proposal

## Weeek 6: Algorithmic Image Generation 

### Before there was deep learning there was...

Jack Wiig [Coloring without seeeing: A problem in machine creativity](http://www.kurzweilcyberart.com/aaron/hi_essays.html)

Kevin Chan [Painterly Rendering for Video and Interaction](http://www.heathershrewsbury.com/dreu2010/wp-content/uploads/2010/07/PainterlyRenderingForVideoAndInteraction.pdf)

### Video Creation

Cooper Barth [The video-to-video paper](https://arxiv.org/abs/1808.06601)
  
  [The video-to-video video](https://www.youtube.com/watch?v=GRQuRcpf5Gc)

  [A video tutorial on video generation with GANs](https://www.youtube.com/watch?v=-E2N1kQc8MM)


### Creative Computation Systems
[5 Video creation aids](https://www.analyticsindiamag.com/top-5-ai-based-text-to-video-products/)


## Week 7 Algorithmic Image Generation

### Gan
[A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)

Marko Sterbentz [Image Style Transfer Using Convolutional Neural Networks](http://openaccess.thecvf.com/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html)

Thomas Young [GANGogh: Creating Art with GANs](https://towardsdatascience.com/gangogh-creating-art-with-gans-8d087d8f74a1)

### Non Technical Readings
[Google’s psychedelic ‘paint brush’ raises the oldest question in art](https://www.washingtonpost.com/news/innovations/wp/2016/03/10/googles-psychedelic-paint-brush-raises-the-oldest-question-in-art/)

### Creative Computation Systems you can try/build
[The deep dream image generator](https://deepdreamgenerator.com)

[A Practical guide to build your first Deep Dream Experience](https://hackernoon.com/deep-dream-with-tensorflow-a-practical-guide-to-build-your-first-deep-dream-experience-f91df601f479)

[Art Breeder](https://artbreeder.com)

## Week 8: Cross-modal Creation

### Making visuals or music, condition from text 
S [Generative Adversarial Text-to-image Synthesis](http://proceedings.mlr.press/v48/reed16.pdf)

S [StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks](https://arxiv.org/abs/1612.03242)
  
  [A video explanation of StackGAN](https://www.youtube.com/watch?v=gmvRStL_Dag)

Jayden Soni [Conditional LSTM-GAN for Melody Generation from Lyrics](https://arxiv.org/abs/1908.05551)

S [Algorithmic Songwriting with ALYSIA](https://arxiv.org/pdf/1612.01058.pdf)

[The Alysia app](https://www.withalysia.com)

Gabriel Caniglia [Image-to-image translation with conditional adversarial networks](http://openaccess.thecvf.com/content_cvpr_2017/html/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.html)
### Non Technical Readings

### Creative Computation Systems
[Sourcecode for Conditional LSTM-GAN for Melody Generation from Lyrics](https://github.com/yy1lab/Lyrics-Conditioned-Neural-Melody-Generation)

[Demo of Pix2Pix network from the Image-to-Image Translation paper](https://affinelayer.com/pixsrv/)

## Week 9: Text and story generation

### Technical Readings 
S [Attention models: AKA Transformer networks: Attention is all you need (academic)](https://arxiv.org/abs/1706.03762)

Sarah Ahmad [Narrative Planning: Balancing Plot and Character](https://www.jair.org/index.php/jair/article/view/10669)

Lisa Cox [Event representations for automated story generation with deep neural nets](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/17046/15769)

Alisa Liu[Rationalization: A Neural Machine Translation Approach to Generating Natural Language Explanations](https://dl.acm.org/citation.cfm?id=3278736)

[The Shape of Games to Come: Critical Digital Storytelling in the Era of Communicative Capitalism](https://curve.carleton.ca/cc1202e7-b599-419c-8909-6eb79421b3af) This is a dissertation. So it's long.

### Non Technical Readings
[Popular press on Open AI's writing system](https://www.vox.com/2019/5/15/18623134/openai-language-ai-gpt2-poetry-try-it)

[Open AI has released GPT-2](https://www.theverge.com/2019/11/7/20953040/openai-text-generation-ai-gpt-2-full-model-release-1-5b-parameters)

[The writer in the machine: Automatic story generation](http://machineloveus.com/the-writer-in-the-machine-automatic-story-generation/)

[AI Wrote a Road Trip Novel. Is it a good read?](https://singularityhub.com/2018/10/25/ai-wrote-a-road-trip-novel-is-it-a-good-read/)

You can buy '1 the Road'[here](https://jean-boite.fr/products/1-the-road-by-an-artificial-neural)

### Creative Computation Systems 
[Essaybot](https://www.essaybot.com)

[Open AI's blog about the GPT-2 Language Model](https://openai.com/blog/better-language-models/)

[The actual Open AI GPT-2 Language Model](https://openai.com/blog/gpt-2-1-5b-release/)
[Talk to Transformer](https://talktotransformer.com) lets you write a starting sentence and see a paragraph of GPT-2 text generated in response.

[Sunspring: A 9 minute movie whose script was written by the "Jetson" LSTM](https://www.youtube.com/watch?v=LY7x2Ihqjmc)

## Week 10: NO CLASS (THANSKGIVING) Work on your project

## Week 11: Support rather than supplant? Who owns the work?

### Technical Readings 

Siddhartha Pamidighantam [Fashion++: Minimal Edits for Outfit Improvement](https://arxiv.org/abs/1904.09261)

Katherine O'Toole [Learning to build Natural Audio Production Interfaces](https://www.mdpi.com/2076-0752/8/3/110/htm)

S [(iGAN) Generative Visual Manipulation on the Natural Image Manifold](http://people.csail.mit.edu/junyanz/projects/gvm/)

### Non Technical Readings

### Creative Computation Systems
[Prisma app](https://prisma-ai.com)

[iGan video](https://www.youtube.com/watch?v=9c4z6YsBGQ0)

[iGan source code](https://media.nips.cc/Conferences/2016/Slides/6202-Slides.pdf)



## Getting started with ML coding
[Anaconda](https://www.anaconda.com) is the most popular Python distribution for ML work.

[Jupyter](https://jupyter.org) is the most popular notebok and visualization framework for python ML development.

[Scikit learn](https://scikit-learn.org/stable/) is the most popular general ML framework.  

[The Pytorch homepage](https://pytorch.org) gets you started on the easiest of the popular deep learning frameworks. It has source code, blogs, tutorials.

[The tensorflow homepage](https://www.tensorflow.org) gets you started on the harder popular deep learning framework. It has source code, blogs, tutorials.





