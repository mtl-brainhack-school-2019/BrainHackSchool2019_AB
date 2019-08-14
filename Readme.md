
# EEG preprocessing/processing using MNE-Python

This project uses open-source EEG data collected on a Music Perception and Imagery task.

Music Imagery Information Retrieval: 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo

* [Dropwizard](https://github.com/sstober/openmiir) - Github
* [Dropwizard](https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf) - Article

## Background

I am a PhD student at Concordia University enroll in an Individualized program (intersection of cognitive neurosciences and digital arts/electroacoustics)
My main PhD focus is on electrophysiological correlates of creativity and pareidolia, as well as how to use this knowledge in Brain-Computer Interfaces (BCI)

I chose to work with these data so it provides me with a first hands-on experience with EEG data.
These scripts/notebooks should be reusable for the data I will be collecting in the next few months (hopefully).

## Preprocessing

- [x] Install MNE-Python
- [x] Load the data into a Jupyter Notebook
- [x] Visualize raw signal
- [x] Independant Component Analysis (ICA)
- [x] Artifact rejection using ICA
- [x] Epoching (channel x condition x trial)


## Processing/Feature extraction
### 
- [ ] Compute Power Spectral Density (PSD) averaged by condition
- [ ] Complexity measures averaged by condition for each channel

- [ ] Steady-state-evoked-potential (SS-EP) for each song averaged across subject

![SS-EP from Nozaradan (2011)](https://github.com/mtl-brainhack-school-2019/BrainHackSchool2019_AB/blob/master/nozaradan_2011.png)

- [ ] Beat per minute (BPM) for each song


- [ ] 



## Analyses

- [ ] Compare perceived vs. imagined conditions for each frequency band
- [ ] Compare topomap regions within conditions across participants
- [ ] Compare SS-EP fo binary vs. ternary songs within conditions across participants

- [ ] 

## Deliverables

Commented Jupyter Notebook..
- [ ] For preprocessing and epoching of data
- [ ] For computation of complexity measures and related topomaps
- [ ] 


```
Give examples
```
