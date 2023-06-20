LITERATURE REVIEW

Controller Design for Active Noise Cancellation Headphones Using Raw Experimental Data

Shiang-Hwua Yu and Jwu-Sheng Hu, "Controller design for active noise cancellation headphones using experimental raw data," in IEEE/ASME Transactions on Mechatronics, vol. 6, no. 4, pp. 483-490, Dec. 2001, doi: 10.1109/3516.974862.

Yu and Hu in their paper describe Active Noise Cancellation headphone which is a headphone that creates another noise
of equal amplitude and opposite phase. This noise is then used to eliminate the outside noise, unlike a passive hearing protector.
A one-channel ANC headphone system consists of a loudspeaker, a microphone, amplifiers and  a feedback controller. This configuration was first suggested by Olson and May in 1953. This aimed to minimize noise levels in a small closure around the ear canal. 
In 1986, Wheeler designed the feedback controller of the ANC Headphones by using classical control theory heuristics to shape open loop frequency response. In 1997, Bai and Lee used the H-infinity optimization technique to optimally synthesize the robust controller. Leitch and Tokhi in their 1987 paper, go through the development of ANC systems through history[....]

In the proposed method by Yu and Hu, they describe two exogenous signals: one acoustic noise signal and an electric input signal. The former describes the noise in the system, whereas the latter is the desired information. Therefore, an ANC headphone aims at reproducing the desired input signal while suppressing the noise (signal). 
A microphone is placed inside the ear cup of headphones which picks up the sound entering the ear canal. In order to reduce distortion a high pass filter is used to compensate for the overall feedback system. 
In their method, they use an inverting summer and a pre-amplifier which are responsible for amplification of the microphone signal and summing up signals from the prefilter and microphone.
The loudspeaker uses an audio power amplifier; the two filters used are prefilter and feedback controller which play an important role in ANC headphones. 

The paper then describes the mathematics behind cancelling the Bandlimited White Noise. It aims at reducing the sound pressure level for the white noise from 50-500 Hz. The maximum allowable amplification of interfering noise is 3dB. Without this constraint, the feedback loop may run into oscillation with large loop gain within the control bandwidth which produces an undesirable audible or inaudible sound. After considering important constraints like these, the paper talks about how using a series of fourth-order controller and filters, they eliminate the white noise. 

PATENT REVIEW
https://patentimages.storage.googleapis.com/97/93/fc/19408ed05d22d6/US2043416.pdf 

