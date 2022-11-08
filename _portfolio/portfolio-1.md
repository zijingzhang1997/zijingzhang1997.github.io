---
title: "Hand gesture recognition system by wearable muscle monitoring sensors "
excerpt: "Human Computer Interaction, non-invasive muscle monitoring <br/><img src='/images/RMG/RMG_HGR.gif'>"
collection: portfolio
---

<img src='/images/RMG/RMG_HGR.gif'><br/>
<img src='/images/RMG/setup.png'>  

•	Conventional electromyography (EMG) measures the continuous neural activity during muscle contraction, but lacks explicit quantification of the actual contraction. Here we propose a novel radiomyography (RMG) for continuous muscle actuation sensing that can be wearable and touchless, capturing both superficial and deep muscle groups. 
<img src='/images/RMG/ges23.png'> 
•	We verified RMG experimentally by a forearm wearable sensor for detailed hand gesture recognition. 
<img src='/images/RMG/sigProc.png'> 
•	We first converted the radio sensing outputs to the time-frequency spectrogram, and then employed the vision transformer (ViT) deep learning network as the classification model, which can recognize 23 gestures with an average accuracy up to 99% on 8 subjects. By transfer learning, high adaptivity to user difference and sensor variation were achieved at an average accuracy up to 97%. 
<img src='/images/RMG/timeLag.png'> 
Waveforms recorded from RMG, sEMG for fast finger motion of 150 beats/minute.

RMG has ultra-low latency with the sampling rate readily over 100,000 samples per second (Sps), which is important for dynamic HGR. 
<img src='/images/RMG/RMG_EMG.png'> 
RMG can be used with synchronous EMG to derive stimulation-actuation waveforms for many future applications in kinesiology, physiotherapy, rehabilitation, and human-machine interface. 
<img src='/images/RMG/extension.png'> 
To validate the general applicability of RMG to different skeletal muscles, we further extended the setup to wearable radiooculogram (ROG) on eyes and RMG on legs. 

