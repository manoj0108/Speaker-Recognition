# Speaker-Recognition

Person identification, especially in critical environments, has always been a subject of great interest. However, it has gained a new dimension in a world threatened by a new kind of terrorism that uses social networks (e.g., YouTube) to broadcast its message. In this new scenario, classical identification methods (such as fingerprints or face recognition) have been forcedly replaced by alternative biometric characteristics such as voice, as sometimes this is the only feature available.

The subject leads that a gender-dependent characterization of speakers combined with the use of a set of features derived from the components, resulting from the deconstruction of the voice into its glottal source and vocal tract estimates, will enhance recognition rates when compared to classical approaches.

STEPS:

	Initially we record of vowel “A” as in bat from one male and one female speaker.

	It is in continuous domain, that would be converted into discrete domain and plot the wave form.

	If the plot have bits less than 512, we pad zeros (Zero padding) and compute the DFT of it. By plotting wave, we can observe that male utterance had higher periodicity than female utterance.

![2](https://user-images.githubusercontent.com/69961625/122654994-ae8bc200-d16c-11eb-97f4-b97664cc5ca5.png)
Figure 1:Representation in time domain using Discrete signal.

![3](https://user-images.githubusercontent.com/69961625/122654999-b51a3980-d16c-11eb-9f1f-fdb8343bab0c.png)
Figure 2: Representation of DFT if Discrete signal.

CONCLUSION:

The spectrum of male voice is more periodic as compared to female voice.
Also the difference between the consecutive peaks in male voice are more, so that we can easily differentiate  male and female voice.
