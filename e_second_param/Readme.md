---
keywords: Secondary Parameters
summary:  Secondary Parameters
index:    5
author:   Studio427 Audio
modified: 15.03.2020
---

## Filters action

Below is a representation of how the different filters are applied:

#### Formant:
![](images/custom/curveF.png)
#### Formant + Rejection:
![](images/custom/curveFR.png)
#### Formant + Rejection + Shelves:
![](images/custom/curveFRS.png)




## Main Formant Filter

![](images/custom/mainFormantFilter.png)

The Main Formant Filter allows for independent setting of the different characteristics of a formant. 
 
> Hint: The selected formant appears in the Adaptive Shelf Filter panel.  Ensure that you have selected the good formant in the formant wheel prior any modification. What your hear might not be what you see!

The Main Formant Filter is composed with the four frequencies that characterize a formant, from F0 to F3.

### F0

But this is not trully accurate. F0 corresponds, in fact, to the pitch of the voice. Therefore, it is not necessary for building a formant. Still, F0 can be, in some situation, useful to provide a stronger Gender on the source, although this greatly depends on the material.  

![](images/custom/WARNING.png)

>Hint: F0 is a low frequency, care must be taken in order not to overload the mix.

### F1 & F2

F1 and F2 are the two main frequencies that are necessary so our brain can reconstruct the associated vowel.  

### F3

F3, for its part, helps to add a more realistic imprint. 


### Parameters

Each of the four formant frequencies have three parameters.

- Gain
- Frequency
- Q Factor

These three parameters don't have the same scope:

| Parameter | Setting scope |
| -- | ------ |
| Gain | Common to all formants |
| Frequency | Independent / per formant |
| Q | Independent / per formant |


## Adaptive Rejection Filter

![](images/custom/adaptiveRejectionFilter.png)

The Adaptive Rejection Filter, or ARF, allows to attenuate the signal between the formant frequencies. 
It provides stronger formant imprint by removing "what is not formant" in the material. 
Please note that this is not necessarily a good option as your source can loose its original character. 
Medium setting in the ARF often gives best results.

The term Adaptive means that the frequencies that are cut, are always calculated to be in between those from the Formant Filter

- Between F0 & F1
- Between F1 & F2
- Between F2 & F3


## Adaptive Shelf Filters

![](images/custom/adaptiveShelfFilter.png)

As for the ARF, the Adaptive Shelf Filters follow the selected frequency.  
The selected formant frequency is kept intact, as the shelf is, in fact, outside of it.

> Hint: The shelf frequency is not the selected frequency itself, but everything that is above it for the HiShelf, or below for the LoShelf.


## Level Compensation

![](images/custom/compensation.png)

The gain applied to the formant frequencies can go high, very high...  
This means that a clipping can occur very quickly. 
This is essentially true if the audio source at the input already contains a lot of material in these frequencies.

This is why BlueMouth as been thouroughly designed to compensate for high levels and clipping, and even limit the output if necessary *(see Adaptive Limiter section below)*.

Although care has been taken to keep the signal as straight as possible, the result can change from one source to another.
The "Compensate" knob sets the output level when Intensity is higher than 0%.

>Set Intensity at 0 and remember the level.  Set intensity at 100% and try to match the previous level using the "Compensate" knob.


## Adaptive Limiter

![](images/custom/adaptiveLimiter.png)

The Adaptive Limiter is a powerful weapon against clipping.  
A smart Limitation will be applied to the Formant Frequency if it is going above -1dB, a bit like a dynamic equalizer.  
The Adaptive Limiter will scrutinze the Formant Frequencies so it is always ready if just one frequency is bursting, even when modulating.

The Adaptive Limiter Reduction level is shown in the Gain & Meters section.

> Hint: The Adaptive Limiter worth to be engaged all the time. The goal, obviously, being to keep it as quiet as possible by the mean of the different level settings, like Compensate, Gain, F0-F3, and the input source.


## Gain Control, Input, Output, and Reduction Meters

![](images/custom/gainMeters.png)

The Gain level helps to prevent clipping of the output.

> Hint: The Gain is situated before the Adaptive Limiter in audio the chain.


## Humanizer

![](images/custom/humanizer.png)

Breathe life into BlueMouth.

The Humanizer subtly modulates the formant frequencies independently and randomly.  
This is especially powerful on long notes, or with slow modulation.

![](images/custom/IDEA.png)
> Protip: we like it 3/4 up almost all the time :)

























