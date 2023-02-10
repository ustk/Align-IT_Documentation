---
keywords: Capture Mode
summary:  Capture Mode
index:    5
author:   Studio427 Audio
modified: 10.02.2023
---

# CAPTURE MODE

In order to compute the delays between your different speakers, you need to CAPTURE at least two speakers and select one of them as reference **REF**. 
There is no real difference between selecting the first or the second CAPTURE, except the delay sign will be opposite (the delay sign can be set in the SETTINGS to fit your workflow).

All following CAPTURES will be COMPUTED against the REF. If you want to compare non-REF speakers between them, select ONE of them as REF and re-COMPUTE the delays.

![capture_window](https://github.com/ustk/Align-IT_Documentation/blob/master/images/capture_window.png?raw=true)

### CAPTURES

This is where the CAPTURES are showing.
Each time you record a new CAPTURE, a new row is added.

#### REF selector

Allows you to select which CAPTURE should be your reference.

#### HPF indicator

Indicates the HPF value this CAPTURE has been recorded with.
When COMPUTING, if a CAPTURE does not have the same HPF as the REF does, the indicator will warn you.

#### Signal visualisation (green for REF, orange for delay lines)

Just a simplified representation of the CAPTURE's signal.

#### SELECTION length visualisation

The two SELECTIONS 1 & 2 are represented with variable rectangle length, meaning only these parts of the signals will be compared between two CAPTURES.

- REF SELECTION 1 will be COMPUTED against other CAPTURES SELECTION 1
- REF SELECTION 2 will be COMPUTED against other CAPTURES SELECTION 2

This allows Align-IT to COMPUTE twice the same signals, but two different portions of them. This way you can be certain the DELAY results are consistent and trustable.

#### CORRELATION

This is a visual representation of the CORRELATION curve after COMPUTATION. 
A nice CORRELATION curve should have a low noise on both sides and a clear peak in the middle. It indicates the correlation that as been COMPUTED is strong, thanks to good CAPTURES.
A noisy CORRELATION is a result of noisy or phasy CAPTURES, due to high reverberation, misplacement of the microphone, low signal to noise ratio, low HPF, unadapted noise type, a too short SELECTION length, a too low PRECISION setting, etc...

> It is a good thing to keep an eye and learn how a strong correlation looks like.

#### DELAY result section

This is where the DELAY results that have been computed are showing.
The DELAY result is expressed in SAMPLES, DISTANCE, and DELAY (ms).

The DELAY in millisecond is showing the delay values for both the ACTUAL temperature, and the TARGET temperature as set in the lower panel.

A nice and trustable result shows in green.

>If a capture shows to many differences in the correlation of SELECTION 1 & 2 against the REF, the DELAY result will appear in orange, meaning it cannot be trusted.

#### DELETE button

Simply DELETE this CAPTURE.

> This is undoable and the DELETED CAPTURE will be lost.


### BOTTOM PARAMETERS

![capture_parameters](https://github.com/ustk/Align-IT_Documentation/blob/master/images/capture_parameters.png?raw=true)

#### High Pass Filter (HPF)

The HPF allows you to cut the lowest energy, and roll back the phase issues that often come with it. Since Align-IT performs a phase comparison between two signals, it is not recommanded to let the room or venue interfere with the phase. In reverberated environment, consider setting the HPF to a higher value.

> Filters introduce phase rotations. Because Align-IT compares the phase between two CAPTURES, you want their respective HPF settings to be the same. If a CAPTURE does not have the HPF setting than the REF, the HPF indicator of this CAPTURE will lit up to orange colour, meaning that the resulting DELAY might not be trustable althought the DELAY indicators (which indicates a difference between SELECTION 1 & 2) are green.
Changing the HPF value when CAPTURES have been made will throw a warning to DELETE the previous CAPTURES.

#### SELECTION length

Align-IT COMPUTES two different parts of the same CAPTURES in order to compare the results internally and tell if the resulting delays are trustable or not (green or orange indicators).
The default SELECTION length is set to 30%, which should be enough most of the time. To put more chances on your side in difficult environments, you can freely adjust the SELECTION length to a higher value and re-COMPUTE. Note in this case the COMPUTATION time can increase considerably.

#### PRECISION

Align-IT can COMPUTE with a sample accuracy when set to the highest value 4. Although this is not always required and a PRECISION of 2-3 is generally largely enough and won't change much the delay results (1 sample @ 48kHz => 0.02ms/7mm).

> The PRECISION setting can lead to a longer COMPUTATION time, especially when used with a longer SELECTION.

#### Temperatures

The speed of sound is essentially affected with the temperature.
Since the calibration of a system generally occurs a long time before the show, the temperatures can change, and so will do the delay between speakers.
For the best accuracy, set the ACTUAL temperature when you record the CAPTURES.
Then adjust the TARGET temperature to the temperature that is expected during the show.
You can see the DELAY at TARGET temperature (Targ C°) change in real time as you adjust the value.
This means you can keep the last COMPUTED delays to hand and adjust the TARGET temperature as you go during the day/night, and report the new DELAYS to the processors as you wish.

> Do not change the ATUAL temperature as the temperature changes during the show, or the DELAY at TARGET temperature will not be accurate anymore. ACTUAL temperature has to be the temperature at the time the CAPTURES have been recorded.