---
keywords: Main Parameters
summary:  Main Parameters
index:    4
author:   Studio427 Audio
modified: 15.03.2020
---

## The Ocular, the Eye, and the Mouth...

The three main controls on the interface are:

- The Formant selection wheel (Ocular)
![Formant_Wheel](https://www.staging.studio427audio.com/_documentation/alignit/images/Formant_Wheel.png)
- The Gender setting (Eye)
![Gender](https://www.staging.studio427audio.com/_documentation/alignit/images/Gender.png)
- The Intensity setting (Mouth)
![Intensity](https://www.staging.studio427audio.com/_documentation/alignit/images/Intensity.png)

![](https://www.staging.studio427audio.com/_documentation/alignit/images/WARNING.png)
>Hint: If you cannot move one of these parameters, this is probably due to the fact that it is already being modulated, or at least, is selected as target in the Modulation matrix of the Modulation page.

## The Formant Selection Wheel

The arrow simply allows to morph smoothly between the formants that are displayed around the wheel. 
Formants can be dragged to another place at will. 
A click on any formant directly sets the arrow straight thereon.  


## Loading more formant
By the mean of a right click on a formant, you have access to a wider choice of formant.  
In the popup, you can select fromant one by one to be inserted at the current select place on the wheel.  
Alternatively, you have the posibility to load a full set of formant at once.


## The Gender Parameter

The right eye is the Gender setting. The Gender setting changes the frequencies in the formant following the differences between a female and a male voice characteristics.

Each formant frequencies from F0 to F3 have different ratio applied in order to keep the gender characteristic and prevent from getting a simple pitch changing sensation.  


## The Intensity Parameter

It is possible to see the Mouth acting like a mix setting, although it is not. The Mouth applies different gains to the different frequencies, taking into account, for instance, the Rejection and the Shelve filters. 
Instead of mixing the raw sound with a fully pushed formant, it is a smooth gain transition of all the different filters combined.  


## Main CC Range

Each of the three controls have a CC Start & CC End setting.

- Small arrows for the Formant CC range
![CC_arrows](/images/custom/CC_arrows.png)
- Mars & Venus symbols for the Gender CC range
![CC_genderSigns](/images/custom/CC_genderSigns.png)
- Nostrils for the Intensity CC range
![CC_nostrils](/images/custom/CC_nostrils.png)

This CC Range determines how the 0-127 value of the incoming CC controls the parameter.  

>Hint: It is important to keep in mind that the mouse is not affected by the limits when moving a parameter. This is useful so you can still explore any setting outside these limits.

Changing CC Start or CC End will make the associated parameter to stick to the value you are actually setting. In other words, the parameter follows the new CC limit so you can quickly listen and fix the new value.

>Pro Tip: With a single click/drag on one CC limit knob, you can quickly set both Min & Max

## CC Link & CC Invert

The CC Link and the CC Invert buttons determine how the Formant or the Gender are linked to Intensity.


## Nose Q Setting

The Nose set the general Q ratio of all frequencies.
>Hint: Therefore, the Nose setting respects the formant F0-F3 original setting, only applying a ratio.

The default setting of the Q ratio is 100% (thin Nose), and corresponds to the original formant characteristic.
![Q_Hi](/images/custom/Q_Hi.png)

With a lower value, the Q diminishes, so the frequency bands become larger (thick Nose).
![Q_Lo](/images/custom/Q_Lo.png)


## Formant Smoothing
![](/images/custom/formantSmoothing.png)

The Formant Smoothing setting allows a smoother transition/morphing between formants.  
A lower setting gives fast response time, where a higher value gives a slower response time.  
This setting affects the response of the formants for these scenario:

- Mouse movement
- CC controllers
- ARP
- Key To Formant

![](/images/custom/WARNING.png)
The Formant modulation has its own smoothing setting (Att & Rel)

>Hint: The Formant Smoothing setting on the main interface is repeated in the ARP as well as in the Key To Formant page.  => Moving one or the other as the same result.  Although, it is important to keep in mind that this setting is disengaged when modulating the Formant. In this case, the modulation matrix provides separated Attack & Release setting. When disengaging the modulation of the formant though, the main Smoothing setting is re-engaged automatically.









































