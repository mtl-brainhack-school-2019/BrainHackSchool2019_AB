
# EEG preprocessing/processing using MNE-Python

## Background

I am a PhD student at Concordia University enroll in an Individualized program (intersection of cognitive neurosciences and digital arts/electroacoustics)
My main PhD focus is on electrophysiological correlates of creativity and pareidolia, as well as how to use this knowledge in Brain-Computer Interfaces (BCI)

But...still waiting for my EEG data!

Instead...
Music Imagery Information Retrieval: 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo

* (https://github.com/sstober/openmiir) - Github
* (https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf) - Article

I chose to work with these data so it provides me with a first hands-on experience with EEG data.
The produced scripts/notebooks should be reusable for the data I will be collecting in the next few months (hopefully)
and for anybody interested in using MNE-Python and complexity measures on electrophysiological data.
This project uses open-source EEG data collected on a Music Perception and Imagery task.





## Preprocessing

- [x] Install MNE-Python
- [x] Load the data into a Jupyter Notebook
- [x] Visualize raw signal
- [x] Independant Component Analysis (ICA)
- [x] Artifact rejection using ICA
- [x] Epoching (channel x condition x trial)


## Processing/Feature extraction
 
- [x] Compute Power Spectral Density (PSD) averaged by condition
- [ ] Complexity measures by channel/song/condition/participant

- [ ] Steady-state-evoked-potential (SS-EP) for each song averaged across subject

![SS-EP from Nozaradan (2011)](https://github.com/mtl-brainhack-school-2019/BrainHackSchool2019_AB/blob/master/nozaradan_2011.png)

- [ ] Beat per minute (BPM) for each song


## Analyses

- [ ] Compare perceived vs. imagined conditions for each frequency band
- [ ] Compare PSD topomap between clustered regions
- [ ] Compare complexity measures topomap between clustered regions 
- [ ] Compare complexity measures for each conditions with complexity measures of stimuli 
      (e.g. correlations of stimuli fractality with brain signal fractality)
- [ ] Compare SS-EP for binary vs. ternary songs for each conditions
- [ ] 

## Deliverables

Commented Jupyter Notebook..
- [ ] For preprocessing and epoching of data
- [ ] For computation of complexity measures, PSD and related topomaps
- [ ] Draft of a paper if any promising results!

- [ ] Requirements.txt
- [ ] Wrap-up on Binder


```

```
