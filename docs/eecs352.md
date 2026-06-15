<a name="top"></a>
# CS 352 MACHINE PERCEPTION OF MUSIC AND AUDIO
## Northwestern University Summer 2026 

|[**Top**](#top)   |[**Calendar**](#calendar)  |[**Links**](#links) |[**Readings**](#readings)|

### Course Description
This course covers machine extraction of structure in audio files covering areas such as source separation (unmixing audio recordings into individual component sounds), sound object recognition (labeling sounds), melody tracking, beat tracking, and perceptual mapping of audio to machine-quantifiable measures.

This course is approved for the Breadth Interfaces & project requirement in the CS curriculum.

Prior programming experience sufficient to be able to do laboratory assignments in PYTHON, implementing algorithms and using libraries without being taught to do so (there is no language instruction on Python). Having taken EECS 211 and 214 would demonstrate this experience.

### Course Textbook
[Fundamentals of Music Processing](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

### Time & Place 
Lecture: Mon, Wed, 11am - 12:30pm CST in Technological Institute M164

<!-- June 22-August 30; 10 weeks -->


### Instructors & Office Hours
[Annie Chu](https://anniejchu.github.io)
TBD Mondays [on Zoom](https://northwestern.zoom.us/j/9176709379) or [by appointment](mailto:anniechu@u.northwestern.edu)

### Course Policies 

#### Questions outside of class
Please use [CampusWire](https://campuswire.com) for class-related questions.

<!-- You can join via [LINK](https://campuswire.com/p/GC60B9C54). CODE 2643 -->

#### Grading Policy
You will be graded on a 100 point scale (e.g. 93 to 100 = A, 90-92 = A-, 87-89 = B+, 83-86 = B, 80-82 = B-...and so on). 

There are 4 core axes you will be graded on: assignments (45%), class participation (15%), midterm (10%), final project (30%)

1. Assignments (individual) - jupyter notebook coding homework assignments. There are 4 assignments, I will drop your lowest assignment. This means you can skip any one assignment.
2. Class participation - in-class paper reading activities, discussions, and initial + mid check ins
3. Final Project (individual / pairs) - make something you're interested in! 

Homework and reading assignments are solo assignments and must be your original work. There will sometimes be readings to prep for class activities. Both readings and advanced topic lectures will be defined by student interest and finalized by end of Week 2. Some topics may include generative modeling for music/speech/SFX, audio-language models + understanding, corpus studies, ethics, etc.

**Bring headphones to class! Many class activities will involve listening to and/or recording sound.**
<!-- 
#### Class Participation
There will be two course readings, determined collectively by student interests in Week 1. We are going to follow the role-playing paper reading format of [Jacobson and Raffel](https://colinraffel.com/blog/role-playing-seminar.html). In this format, students read the same paper, but each student takes one specific role for that reading presentation. See a short guide on how to read a [paper](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf). Inspired by Prof. Fuentes' [MIR](https://sed.yox.mybluehost.me/music-information-retrieval/) course. -->

#### AI policy
You are expected to write your own code and write up your own answers to question (not ChatGPT or Gemini or Copilot). This is an optional class you are (presumably) taking because you're interested.

#### Submitting assignments
Assignments must be submitted on the due date by the time specified on Canvas. If you are worried you can't finish on time, upload a safety submission an hour early with what you have. I will grade the most recent item submitted before the deadline. Late submissions will not be graded.


<a name="calendar"></a>
### Course Calendar  

* means subject to change based on student interest

| Week|Date         | Topic                             | Assignment Due      | Points|  
|----:|-------------|-----------------------------------|-----------------|------:|
|1    | Mon June 22   | Course intro, [Recording Basics](eecs352stuff/CS352-topic1-recording-basics.pdf) | Learning Goals + Initial Meeting Sign Ups |   3pts   |    
|1    | Wed June 24   | [Frequency & Pitch](eecs352stuff/CS352-topic4-pitch.pdf), [Tuning Systems](eecs352stuff/CS352-topic5-tuning-systems.pdf) + sound representations (phonemes, sheet music, piano roll, midi) |        |      |    
|2    | Mon June 29  | [Amplitude](eecs352stuff/CS352-topic2-amplitude.pdf) & [Loudness](eecs352stuff/CS352-topic3-loudness.pdf) |        |      |    
|2    | Wed July 1  |  [Fourier Transforms & Spectrograms](eecs352stuff/CS352-topic6-DFT.pdf)   |        |      |    
|3    | Mon July 6  |  [Convolution](eecs352stuff/CS352-topic8-convolution.pdf) & [Filtering](eecs352stuff/CS352-topic9-filtering.pdf) // [Convolution & FFT notebooks](eecs352stuff/convolution_and_fft_notebook.zip)  | HW 1 Audio Basics   |     15 |    
|3    | Wed July 8  | Advanced Filtering: [Source Separation w/ REPET](eecs352stuff/CS352-topic10-REPET-SIM.pdf) |        |      |    
|3    | Mon July 13   | [MFCCs and Chromagrams](eecs352stuff/CS352-topic7-Chroma-Cepstra.pdf) // [MFCC + Chroma notebooks](eecs352stuff/NUCS352_chromagram_mfcc_notebook.zip) |        |      |    
|4    | Wed July 15  | [Self-Similarity](https://pseeth.github.io/public/lectures/self-similarity.html) | HW 2 Spectrograms, Masking | 15 | 
|4    | Mon July 20  | [(Beat) + Pitch Tracking](eecs352stuff/CS352-Single-Pitch-Detection.pdf) |    |     |    
|5    | Wed July 22   | [Basic Classifiers (Sound Object Labeling)](eecs352stuff/CS352-topic11-sound-object-id.pdf) | HW 3 Infinite Jukebox | 15 |
|5    | Mon July 27   | MIDTERM Check-In (exam; 10) / check in (5 pts) | Midterm |   10   | 
|6    | Wed July 29   | [Deep Learning](eecs352stuff/CS352-topic12-deep-nets.pdf) & [Autoencoders](eecs352stuff/DL_Autoencoders.pdf)   |   | |    
|6    | Mon Aug 3  | [Embeddings](eecs352stuff/CS352-embeddings.pdf) & [Embeddings Notebook](eecs352stuff/NUCS352_clap_embeddings_notebook.zip) & Final Project Overview |    |      |  
|7    | Wed Aug 5  | Building Interactive Music Systems (HCI for Musicking) |   HW 4 Using Embeddings    |  15  |
|7    | Mon Aug 10  |  Workshopping Proposals  | Project Proposal Due (EOD) | 5 (of 30)   |
|8    | Wed Aug 12  | *Advanced Topics (TBD)* + Project Workshop |  |      |    
|8    | Mon Aug 17  | Zoom meetings with project groups (no class: meetings by appointment) | Project Meeting 1  | (5 of 30) |    
|9    | Wed Aug 19   | *Advanced Topics (TBD)* + Project Workshop |  |   |   
|10   | Mon Aug 24  | Zoom meetings with project groups (no class: meetings by appointment)| Project Meeting 2 | 5 of (30) | 
|10   | Wed Aug 26  | FINAL PROJECT PRESENTATIONS    |            | Deliverables (15 of 30) |  

<a name="readings"></a>

### Course Reading 
 
[Fundamentals of Music Processing, Chapter 1](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

[Fundamentals of Music Processing, Chapter 2 & Section 3.1](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

[Fundamentals of Music Processing, Chapter 4](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

[Fundamentals of Music Processing, Chapter 6](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

[Fundamentals of Music Processing, Chapter 7](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

[* REPET for Background/Foreground Separation in Audio](https://interactiveaudiolab.github.io/assets/papers/Rafii-Liutkus-Pardo%20-%20REPET%20for%20Background-Foreground%20Separation%20in%20Audio%20-%20Springer%202014.pdf)

[Chapter 4 of Machine Learning ](eecs352stuff/chapter4-ml.pdf): This is Tom Mitchell's book. Historical overview + explanation of backprop of error. It's a good starting point for actually understanding deep nets. 

[Yin: a fundamental frequency estimator for speech and music](https://asa.scitation.org/doi/pdf/10.1121/1.1458024) - This is, perhaps, the most popular pitch tracker.

[Crepe: A Convolutional Representation for Pitch Estimation](https://ieeexplore.ieee.org/abstract/document/8461329) - A deep learning pitch tracker that improves on Yin.

[The dummy’s guide to MFCC](https://medium.com/prathena/the-dummys-guide-to-mfcc-aceab2450fd) - an easy, high-level read. Start with this.

[From Frequency to Quefrency: A History of the Cepstrum](https://www.fceia.unr.edu.ar/prodivoz/Oppenheim_Schafer_2004.pdf) - a historical analysis of the uses of cepstrums

[Recovering sound sources from embedded repetition](http://mcdermottlab.mit.edu/papers/McDermott_Wrobleski_Oxenham_2011_source_repetition.pdf) - This is a paper on how humans actually listen to and parse audio based on repetition. Read any time.


<a name="links"></a>

### Helpful Links

#### Places to get ideas
[EECS 352 Final projects from 2017 and 2015](http://www.cs.northwestern.edu/~pardo/courses/eecs352/projects.php)

[Google's Project Magenta](https://magenta.tensorflow.org)

[Facebook's Universal Music Translation](https://research.fb.com/facebook-researchers-use-ai-to-turn-whistles-into-orchestral-music-and-power-other-musical-translations/)

[A coursera corse on pitch tracking](https://www.coursera.org/lecture/audio-signal-processing/pitch-detection-Vr9du)

#### Datasets
[U of Iowa's Music Instrument Samples Dataset](http://theremin.music.uiowa.edu/MIS.html)

[The SocialFX data set of word descriptors for audio](http://music.cs.northwestern.edu/data/socialfx/)

[VocalSet: a singing voice dataset consisting of 10.1 hours of monophonic recorded audio of professional singers](https://zenodo.org/record/1442513#.XDIwoi2ZOqQ)

[VocalSketch: thousands of vocal imitations of a large set of diverse sounds](https://zenodo.org/record/1251982#.XDIw6i2ZOqQ)

[Bach10: audio recordings of each part and the ensemble of ten pieces of four-part J.S. Bach chorales](https://docs.google.com/forms/d/e/1FAIpQLSfJ1IdB7Ws2_m0wkkvS1hGm5GevGS3QmqBIoxiGDbw93yoPLQ/viewform?embedded=true&formkey=dGU3cmRlb1Q4RU5zTGNZeHUyRGFwaWc6MQ)

[The Million Song Dataset](https://labrosa.ee.columbia.edu/millionsong/)

#### Software 
[Python Utilities for Detection and Classification of Acoustic Scenes](https://dcase-repo.github.io/dcase_util/index.html)

[Librosa audio and music processing in Python](https://librosa.github.io)

[Essentia: an open source music analysis toolkit](https://essentia.upf.edu/documentation/) includes a bunch of feature extractors and pre-trained models for extracting e.g. beats per minute, mood, genre, etc.

[Yaafe - audio features extraction toolbox](http://yaafe.sourceforge.net)

[Sonic Visualizer music viz software](https://www.sonicvisualiser.org)

[Lily Pond, open source music notation software](http://lilypond.org)

[SoundSlice guitar tab and notation website](https://www.soundslice.com)


|[**Top**](#top)   |[**Calendar**](#calendar)  |[**Links**](#links)  |[**Readings**](#readings)|


[papers](https://arxiv.org/pdf/2410.00872)


<!-- | Week|Date         | Topic                             | ASSIGNMENT      | Points|
|----:|-------------|-----------------------------------|-----------------|------:|
|1    | Mon June 22   | Course intro, [Recording Basics](eecs352stuff/CS352-topic1-recording-basics.pdf) | Learning Goals + Initial Meeting Sign Ups |   3pts   |    
|1    | Wed June 24   | Signal Basics: [Frequency & Pitch](eecs352stuff/CS352-topic4-pitch.pdf), [Tuning Systems](eecs352stuff/CS352-topic5-tuning-systems.pdf) + sound representations (phonemes, sheet music, piano roll, midi) |        |      |    
|2    | Mon June 29  | Signal Basics: [Amplitude](eecs352stuff/CS352-topic2-amplitude.pdf) & [Loudness](eecs352stuff/CS352-topic3-loudness.pdf) |        |      |    
|2    | Wed July 1  | Signal Analysis: [Fourier Transforms & Spectrograms](eecs352stuff/CS352-topic6-DFT.pdf)   |        |      |    
|3    | Mon July 6  | Signal Analysis: [Convolution](eecs352stuff/CS352-topic8-convolution.pdf) & [Filtering](eecs352stuff/CS352-topic9-filtering.pdf) // [Convolution & FFT notebooks](eecs352stuff/convolution_and_fft_notebook.zip)  | HW 1 Audio Basics   |     15 |    
|3    | Wed July 8  | Music Classification: [MFCCs and Chromagrams](eecs352stuff/CS352-topic7-Chroma-Cepstra.pdf) // [MFCC + Chroma notebooks](eecs352stuff/NUCS352_chromagram_mfcc_notebook.zip) |        |      |    
|4    | Mon July 13  | [(Self-)Similarity](https://pseeth.github.io/public/lectures/self-similarity.html) | HW 2 Spectrograms, Masking | 15 | 
|4    | Wed July 15  | Algorithms: [(Beat) + Pitch Tracking](eecs352stuff/CS352-Single-Pitch-Detection.pdf), [Source Separation w/ REPET](eecs352stuff/CS352-topic10-REPET-SIM.pdf)  |    |     |    
|5    | Mon July 20   | [Basic Classifiers & Sound Object Labeling](eecs352stuff/CS352-topic11-sound-object-id.pdf) | HW 3 Infinite Jukebox | 15 |
|5    | Wed July 22  | MIDTERM Check-In (oral, on Zoom) | Midterm |   10   | 
|6    | Mon July 27  | [Deep Learning](eecs352stuff/CS352-topic12-deep-nets.pdf) & [Autoencoders](eecs352stuff/DL_Autoencoders.pdf)   |   | |    
|6    | Wed July 29  | [Embeddings](eecs352stuff/CS352-embeddings.pdf) & [Embeddings Notebook](eecs352stuff/NUCS352_clap_embeddings_notebook.zip)|    |      |    
|7    | Mon Aug 3  | Building Interactive Music Systems (HCI for Musicking) |   HW 4 Using Embeddings    |  15  |
|7    | Wed Aug 5  |  Final Project Overview + group formation   |  |  |
|8    | Mon Aug 10  | *Special Topics: Music Recommendation Systems + RP-Paper Reading 1 | Project Proposal Due |    5 (of 30)    |    
|8    | Wed Aug 12  | Zoom meetings with project groups (no class: meetings by appointment) | Project Meeting 1  | (5 of 30) |    
|9    | Mon Aug 17   | *Special Topics: Audio Language Models + RP-Paper Reading 2 |  |   |    
|9    | Wed Aug 19   | Zoom meetings with project groups (no class: meetings by appointment)| Project Meeting 2 | 5 of (30) |    
|10   | Mon Aug 24  | *Special Topics: Generative Audio Models |          |           |    
|10   | Wed Aug 26  | FINAL PROJECT PRESENTATIONS    |            | Deliverables (15 of 30) |  
