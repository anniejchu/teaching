<a name="top"></a>
# CS 352 MACHINE PERCEPTION OF MUSIC AND AUDIO
## Northwestern University Winter 2026 

|[**Top**](#top)   |[**Calendar**](#calendar)  |[**Links**](#links) |[**Readings**](#readings)|

### Course Description
This course covers machine extraction of structure in audio files covering areas such as source separation (unmixing audio recordings into individual component sounds), sound object recognition (labeling sounds), melody tracking, beat tracking, and perceptual mapping of audio to machine-quantifiable measures.

This course is approved for the Breadth Interfaces & project requirement in the CS curriculum.

Prior programming experience sufficient to be able to do laboratory assignments in PYTHON, implementing algorithms and using libraries without being taught to do so (there is no language instruction on Python). Having taken EECS 211 and 214 would demonstrate this experience.

### Course Textbook
[Fundamentals of Music Processing](https://link.springer.com/book/10.1007%2F978-3-319-21945-5)

### Time & Place 
Lecture: Tue, Thu, 3:30 - 4:50pm CST in 2122 Sheridan Rd Classroom 250

### Instructors & Office Hours
[Prof. Bryan Pardo](http://bryanpardo.com) 
10am - 11am Thursdays in Mudd 3115

[TA Annie Chu](https://anniejchu.github.io)
11am - 1pm Tuesdays in Mudd 3202

[Peer Mentor] EJ Van De Grift
2pm - 3pm Wednesdays in Mudd 3108

[Postdoc Jason Smith](https://scholar.google.com/citations?user=1R0IoRMAAAAJ&hl=en)
Jason Smith will help guide final projects.


### Course Policies 

#### Questions outside of class
Please use [CampusWire](https://campuswire.com) for class-related questions.

#### Grading Policy
You will be graded on a 100 point scale (e.g. 93 to 100 = A, 90-92 = A-, 87-89 = B+, 83-86 = B, 80-82 = B-...and so on). 

Every assignment is worth 20 points. There are 5 assignments (including the final project). Your final grade will be the sum of midterm grade + your 4 highest assignment grades. This means you can skip any one assignment.

Homework and reading assignments are solo assignments and must be your original work. 

#### AI policy
You are expected to write your own code and write up your own answers to question. This means you. Not ChatGPT or Gemini or Copilot. This is an optional class you are (presumably) taking because you're interested. So put in the time to learn this stuff, yourself.

#### Submitting assignments
Assignments must be submitted on the due date by the time specified on Canvas. If you are worried you can't finish on time, upload a safety submission an hour early with what you have. I will grade the most recent item submitted before the deadline. Late submissions will not be graded.


<a name="calendar"></a>
### Course Calendar  

| Week|Date         | Topic                             | ASSIGNMENT      | Points|
|----:|-------------|-----------------------------------|-----------------|------:|
|1    | Tue Jan 6   | Course intro, [Recording basics](eecs352stuff/CS352-topic1-recording-basics.pdf)                                          |        |      |    
|1    | Thu Jan 8   | [Frequency & Pitch](eecs352stuff/CS352-topic4-pitch.pdf), [Tuning Systems](eecs352stuff/CS352-topic5-tuning-systems.pdf)  |        |      |    
|2    | Tue Jan 13  | [Loudness](eecs352stuff/CS352-topic3-loudness.pdf) & [Amplitude](eecs352stuff/CS352-topic2-amplitude.pdf)                 |        |      |    
|2    | Thu Jan 15  | [Fourier Transforms & Spectrograms](eecs352stuff/CS352-topic6-DFT.pdf)                                                    |        |      |    
|3    | Tue Jan 20  | [Convolution](eecs352stuff/CS352-topic8-convolution.pdf) & [Filtering](eecs352stuff/CS352-topic9-filtering.pdf)           | HW 1 Audio Basics           |     20 |    
|3    | Thu Jan 22  | [Convolution & FFT notebooks](eecs352stuff/convolution_and_fft_notebook.zip)                                              |        |      |    
|4    | Tue Jan 27  | [SOURCE SEPARATION WITH REPET](eecs352stuff/CS352-topic10-REPET-SIM.pdf)                                                              |                            |      | 
|4    | Thu Jan 29  | [MFCCs and Chromagrams](eecs352stuff/CS352-topic7-Chroma-Cepstra.pdf) & [MFCC & Chroma notebooks](eecs352stuff/NUCS352_chromagram_mfcc_notebook.zip)    |    |    |    
|5    | Tue Feb 3   | [Self Similarity](https://pseeth.github.io/public/lectures/self-similarity.html)           | HW 2 Spectrograms, Masking |  20  |
|5    | Thu Feb 5   | MIDTERM REVIEW  + [Pitch Tracking](eecs352stuff/CS352-Single-Pitch-Detection.pdf)          |                            |      | 
|6    | Tue Feb 10  | MIDTERM                                                                                    | MIDTERM                    |   20 |    
|6    | Thu Feb 12  | [Sound Object Labeling](eecs352stuff/CS352-topic11-sound-object-id.pdf)                    |                            |      |    
|7    | Tue Feb 17  | [Deep Learning](eecs352stuff/CS352-topic12-deep-nets.pdf) & [Autoencoders](eecs352stuff/DL_Autoencoders.pdf)                                 | HW 3 Infinite Jukebox      |   20 |
|7    | Thu Feb 19  | [Embeddings](eecs352stuff/CS352-embeddings.pdf) & [Embeddings Notebook](eecs352stuff/NUCS352_clap_embeddings_notebook.zip) |  |  |
|8    | Tue Feb 24  | Final projects, VoiceID, Source Separation                                                 |                            |      |    
|8    | Thu Feb 26  | Final project group formation & proposals                                                  | HW 4 Using Embeddings      |        20 |    
|9    | Tue Mar 3   | Current research in music & audio (Annie)                                                  | Project proposal due       | 3 (of 20) |    
|9    | Thu Mar 5   | Zoom meetings with project groups (no class: meetings by appointment)                      | Project meeting            | 3 (of 20) |    
|10   | Tue Mar 10  | Current research in music & audio                                                          |                            |           |    
|10   | Thu Mar 12  | Zoom meetings with project groups (no class: meetings by appointment)                      | Project meeting            | 3 (of 20) |  
|11   | Wed Mar 18  | Final project presentations 7-9pm NEW LOCATION: HCI+D Center in Francis Searle Building                          | Final project              | 11(of 20) |


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
