---
title: "Continuous and simultaneous estimation of finger kinematics using inputs from an EMG-to-muscle activation model"
collection: publications
permalink: /publication/2013_jner_ngeo
venue: "Journal of NeuroEngineering and Rehabilitation"
date: 2015-08-25
citation: '<b>Jimson Ngeo</b>, Tomoya Tamei, Tomohiro Shibata. <i>Journal of NeuroEngineering and Rehabilitation</i>.'
paperurl: 'https://jneuroengrehab.biomedcentral.com/articles/10.1186/1743-0003-11-122'

---  
[[PDF]](https://jneuroengrehab.biomedcentral.com/track/pdf/10.1186/1743-0003-11-122?site=jneuroengrehab.biomedcentral.com) [[Code]]()

## Abstract
Abstract
Background
Surface electromyography (EMG) signals are often used in many robot and rehabilitation applications because these reflect motor intentions of users very well. However, very few studies have focused on the accurate and proportional control of the human hand using EMG signals. Many have focused on discrete gesture classification and some have encountered inherent problems such as electro-mechanical delays (EMD). Here, we present a new method for estimating simultaneous and multiple finger kinematics from multi-channel surface EMG signals.

Method
In this study, surface EMG signals from the forearm and finger kinematic data were extracted from ten able-bodied subjects while they were tasked to do individual and simultaneous multiple finger flexion and extension movements in free space. Instead of using traditional time-domain features of EMG, an EMG-to-Muscle Activation model that parameterizes EMD was used and shown to give better estimation performance. A fast feed forward artificial neural network (ANN) and a nonparametric Gaussian Process (GP) regressor were both used and evaluated to estimate complex finger kinematics, with the latter rarely used in the other related literature.

Results
The estimation accuracies, in terms of mean correlation coefficient, were 0.85±0.07, 0.78±0.06 and 0.73±0.04 for the metacarpophalangeal (MCP), proximal interphalangeal (PIP) and the distal interphalangeal (DIP) finger joint DOFs, respectively. The mean root-mean-square error in each individual DOF ranged from 5 to 15%. We show that estimation improved using the proposed muscle activation inputs compared to other features, and that using GP regression gave better estimation results when using fewer training samples.

Conclusion
The proposed method provides a viable means of capturing the general trend of finger movements and shows a good way of estimating finger joint kinematics using a muscle activation model that parameterizes EMD. The results from this study demonstrates a potential control strategy based on EMG that can be applied for simultaneous and continuous control of multiple DOF(s) devices such as robotic hand/finger prostheses or exoskeletons.
