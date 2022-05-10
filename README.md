# Deep Noise Suppression

## Team Members
**ChengHan Chung** (chenghan.chung@ut.ee),
**Ashraf Abbasov** (ashraf.abbasov@ut.ee),
**Ayushmat Bhardwaj Soni** (ayushmat.soni@ut.ee),
**Lukas Andrijauskas** (lukas.andrijauskas@ut.ee)

## Motivation
Now a day, telecommuting has become the ”new normal” as people working remotely (e.g., attend-ing project meeting or participating online course) has increased significantly due to the COVID pandemic. Hence, there is a surge in the demand for reliable collaboration and real-time communi-cation tools. Excellent speech quality in audio or video calls are needed during these times. Howev-er, we are often exposed to a variety of background noises, for example, dog barking, baby crying, traffic noises, neighboring talkers, etc., which may significantly degrade the quality and intelligibility of the perceived speech and lead to increased fatigue in virtual meetings. Therefore, noise suppres-sion for improving the perceptual quality of speech is the potential topic to provide the solution of this issue.

## Datasets
The data will be source from the Microsoft challenge[1], which include the raw clean speech, noise, and impulse responses dataset. The clean speech consists of English read-speech, English singing voice, French, German, Italian, Russian and Spanish languages. The clean speech datasets are fil-tered with DNS-MOS P.835 OVRL score greater than 4.25. The noise dataset are with no presence of speech. The impulse responses dataset can be leveraged for generating reverberant noisy train-ing data. By time consuming, this time, we will just use English speech voice as data set in the pro-ject.

## Method
Deep learning models are becoming attractive and powerful choices for noise suppression. Hence, we will implement the idea and concept we learned in the course for speech enhancement in real-time applications. In this project work, we try to build-up reasonably small recurrent and convolution-al-recurrent network architectures for achieving enhance speech quality and background noise re-duction. The subjective evaluation in project will use MOS (Mean Opinion Score) [2], which is a non-intrusive speech quality metric, to evaluate speech quality (SIG), background noise quality (BAK), and the overall quality (OVRL) of the audio.

## Reference
[1]	Deep Noise Suppression Challenge – ICASSP 2022 (https://www.microsoft.com/en-us/research/academic-program/deep-noise-suppression-challenge-icassp-2022/)

[2]	Reddy, C. K., Gopal, V., & Cutler, R. (2021). DNSMOS P. 835: A non-intrusive perceptual objective speech quality metric to evaluate noise suppressors. arXiv preprint arXiv:2110.01763
