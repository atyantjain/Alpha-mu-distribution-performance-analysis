# Alpha-mu-distribution-performance-analysis
This repository contains codes about the performance analysis of the Alpha-mu distribution channel model in free space optical communication

THE CODES ARE MUPAD CODES TO BE RUN IN MATLAB

Abreviations:
OP = outage probablity
CAV = Average Channel capacity

INTRODUCTION:
Most of existing wireless and mobile communication systems exploit the radio and microwave frequency bands that became extremely overcrowded.The demand of bandwidth and channel capacity in wireless communication has increased so tremendously that we have to shift from Radio Frequency band to Infrared band. In infrared wireless communication system, optical beams are transmitted in free space instead of optical link. This is known as FSO system.FSO has a huge bandwidth that makes it an attractive solution for the bandwidth consumption issue. Free- space optics, also known as wireless optical, is a potentially high-capacity and cost- effective communication technique, which has been receiving attention and commercial interest.
FSO communication system is not subjected to any license regulation. It has many advantages like high data rate, large bandwidth, less power requirement, low attenuation level, high transmission security etc. It is easily installed, light weight and expandable as compared to conventional optical fiber cables. However, the main performance confining factor in FSO communication system is the degradation of transmitted beam as it propagates through turbulent atmosphere. When optical laser beam transmits from one-point source to another in free space then it is easily affected by various parameters like scattering, absorption, divergence, atmospheric losses and atmospheric turbulence. 

CHANNEL MODEL:
According to the temperature and pressure gradients, there are irradiance fluctuations in the received signal which results in distortion and beam broadening of received spectrum. As per the different levels of turbulent conditions such as weak (where S.I<1), moderate (where S.I=1), strong (where S.I>1), various statistical various statistical channel models for transmission in free space are developed. The channel model is modelling the transmission path between transmitter and receiver. Wide ranges of statistical model are proposed to model the channel in FSO communication system over the years. Earlier, Negative Exponential and Log Normal distribution is widely used for strong and weak turbulence condition respectively. 

ALPHA-MU DISTRIBUTION:
The fading model for the α-μ distribution considers a signal composed of clusters of multipath waves propagating in a non-homogeneous environment. Within any one cluster, the phases of the scattered waves are random and have similar delay times with delay-time spreads of different clusters being relatively large. The clusters of multipath waves are assumed to have the scattered waves with identical powers. The resulting envelope is obtained as a nonlinear function of the modulus of the sum of the multipath components. Such a non-linearity is manifested in terms of a power parameter, so that the resulting signal intensity is obtained not simply as the modulus of the sum of the multipath components, but as this modulus to a certain given exponent.

OUTAGE PROBABLITY (OP):
The availability of an FSO channel can be described by its outage probability, Pout. This is a particularly significant metric for any wireless link since it represents the probability that the instantaneous SNR at the receiver’s input falls below a critical threshold, 𝛾𝑡h, which corresponds to the receiver’s sensitivity limit.
𝑃 =𝑃𝑟(𝛾≤𝛾 )=𝐹(𝛾 )

AVERAGE CHANNEL CAPACITY (CAV):
The average, or ergodic, capacity of a channel represents the mean achievable capacity of a common link. More specifically, it is the magnitude which corresponds to the real – practical – upper bound of the data that can propagate through the channel for the specific FSO link and atmospheric conditions for the cases of fast fading statistics. The average capacity 𝐶𝑎𝑣, of an FSO communication link, assuming that the propagating path is an AWGN channel, is given by:
𝐶 = ∫∞𝐵 log (1+(𝜂𝐼)2)𝑓(𝐼)𝑑𝐼

USING THIS INFORMATION THE CAV AND OP FOR ALPHA-MU WERE DERIVED AND SIMULATED ON MATLAB-MUPAD USING THE ATTACHED CODES.
