---
keywords: Top Menu
summary:  Top Menu
index:    4
author:   Studio427 Audio
modified: 10.02.2023
---

### Selecting the noise type

![top_menu_noise_type](https://github.com/ustk/Align-IT-DOCUMENTATION/blob/master/images/top_menu_noise_type.png?raw=true)

Align-IT offers 3 types of noises to CAPTURE your speakers.

- **WHITE** noise
- **VIOLET** noise
- **IMPULSE** noise

### WHITE noise

The most common and versatile type of noise to make your CAPTURES. In general environments, the WHITE noise should work the best.
Although with reverberating venues, it can sometimes lead to too many phase issues and wrong results.
If you encounter non accurate results, you can try first to raise the High Pass Filter (HPF) before recording.
If this is not enough, consider using the VIOLET or IMPULSE types.

### VIOLET noise

The VIOLET noise type contains far less low energy compared to WHITE noise, hence produces less phases issues in highly reverberating environments.

### IMPULSE noise

The WHITE noise and VIOLET noise should cover all your needs in most cases. Although in some situations, like noisy environment, falling back to IMPULSES can give great results.
IMPULSE CAPTURES generally require a longer SELECTION to COMPUTE.

### Main Controls

![top_menu_capture](https://github.com/ustk/Align-IT-DOCUMENTATION/blob/master/images/top_menu_capture.png?raw=true)

### PLAY

The PLAY button allows you to play the currently selected noise type to optimise your levels before recording the CAPTURES.
As the noise is only 1sec length, you might want to PLAY in LOOP by clicking the LOOP symbol on the left of the PLAY button.

> The loop is noticeable when playing, this is totally normal as Align-IT requires a perfectly correlated noise for its operations. In ANALYSER mode, the noise that is playing isn't the same as in CAPTURE mode.

### CAPTURE

This triggers the CAPTURE of the speaker you routed the signal to for one second.
CAPTURE as many speakers as you need, including the reference one.
Be sure you have adjusted the HPF before recording the CAPTURES so they all have the same HPF.

### COMPUTE

Once all the speakers have CAPTURED, this triggers the COMPUTATION of all the delays.
Select the reference REF and start COMPUTING the DELAYS.

If the results are not consistent enough, consider adusting the SELECTION length and PRECISION, in the lower panel (for more information, see the Lower Panel section).

> Be sure you have adjusted the ACTUAL temperature prior to starting COMPUTATION.

### Export Data

![top_menu_export](https://github.com/ustk/Align-IT-DOCUMENTATION/blob/master/images/top_menu_export.png?raw=true)

### CSV & TXT

Once the DELAYS have been COMPUTED, you can export the results as .csv and .txt files so it is easier to bring the results to the processors if needed.
To open the FOLDER that contains all the exports, click the FOLDER button on the far right of the menu.

> For less confusion, you can name the SHOW and the individual CAPTURES.

### DELETE

This will DELETE all the current CAPTURES.

> This is undoable and all CAPTURES and COMPUTED DELAYS will be lost !