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

Dr Lawrence J. Fogel is generally credited with inventing active noise cancellation, but noise-cancelling headphones the way we know them today were invented by Dr. Amar Bose of Bose Corporation during the 1980s. Similar to the circuit described above, the headset that the Bose corporation was working on consisted of a microphone which capture the sound and measured the frequency and amplitude of the soundwave to create an opposite soundwave and thus used destructive interference to cancel the noise. These headsets were first designed for the Voyager flight by Dick Rutan and Jeana Yeager who were circumnavigating the globe without refueling. 

On May 11, 202 the Bose Corporation filed a patent for Synchronization of instability mitigation in audio devices. It was a method that is used in control audio devices with active noise reduction (ANR). The system is designed to detect instability conditions in a first headphone and generates one or more control signals to adjust the ANR parameters. The first ANR state is then adjusted to change it into the second ANR state to mitigate the instability condition. 

https://patentimages.storage.googleapis.com/97/93/fc/19408ed05d22d6/US2043416.pdf 

http://daimlerferret.co.uk/wp-content/uploads/2022/07/The-history-of-ANR-noise-cancellation.pdf

https://dspace.mit.edu/bitstream/handle/1721.1/33284/62276966-MIT.pdf?sequence=2

https://www.electronicproducts.com/active-noise-cancellation-anc-block-diagram/
