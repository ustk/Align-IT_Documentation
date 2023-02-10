---
keywords: Analyser Mode
summary:  Analyser Mode
index:    6
author:   Studio427 Audio
modified: 10.02.2023
---

![analyser_window](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_window.png?raw=true)

### SPECTRUM

The spectrum window shows you the main FAST and SLOW curves as well as the COLLECTION memories.
The window can be set in full view or split view.
On the right, the RANGE Slider allows you to zoom vertically and move the spectrum.
Screenshots of the spectrums can be exported to the export folder location

> The SLOW curve can be customised (smooth, slope, dots/bargraph) using the BALLISTIC parameters.

### BOTTOM PARAMETERS

![analyser_parameters](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_parameters.png?raw=true)

#### COLLECTION

![analyser_collection](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_collection.png?raw=true)

In the COLLECTION, you can store up to 8 SLOW curves that will be recalled next time until you delete them.

#### MAIN

![analyser_main](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_main.png?raw=true)

Allows you to display the FAST and the SLOW spectrum.

#### DISPLAY

![analyser_display](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_display.png?raw=true)

Allows you to set the frequency style and gain lines, toggle between split and full view, and export screenshots.

The freqeuncy style are:

- **NATURAL** (logarithmic)
- **31 BANDS** (represent the most common 31 bands of equalisers)
- **15 BANDS** (represent the most common 15 bands of equalisers)

> The 31 BANDS might not align with the curve when it is set to 1/3 OCTAVE smoothing. This is perfectly normal since the chosen bands for equalisers are rounded to the closest frequencies, while a real third octave analyser like Align-IT sets the spectrum frequencies using a strict mathematical function.

#### BALLISTIC

![analyser_ballistic](https://github.com/ustk/Align-IT_Documentation/blob/master/images/analyser_ballistic.png?raw=true)

##### DECAY

Sets the speed of the FAST and the SLOW spectrums

##### AUTOCENTER

Keeps the SLOW curve always in the middle of the sreen

> For SLOW curve only

##### BUFFER

Sets the buffer size for both the FAST and the SLOW spectrums.

- Smaller buffers give a more reacting visualisation
- Larger buffers give more details in the low end

> When using a small buffer size, be careful to what you see in the low end. This might not translate the reality well.

##### SLOPE

Tilts the SLOW spectrum if you want to tune the venue to a specific frequency response, or want a flat visualisation of the material during the show.

> For SLOW curve only

##### CURVE/DOT/BAR

Sets the SLOW spectrum type when SMOOTH is set to something else than OFF.

> For SLOW curve only

##### SMOOTH

**OFF:**
None of the above parameters are affecting the spectrum (except DECAY, AUTOCENTER and BUFFER).

**1/12th to OCATVE:**
Apply a smoothing to the SLOW spectrum curve.

> For SLOW curve only