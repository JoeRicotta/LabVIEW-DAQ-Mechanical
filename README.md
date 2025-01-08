# LabView-DAQ-Mechanical
LabVIEW &amp; Arduino code for Intrinsic Optical Signal Imaging rig with PCO camera integration

These files are mostly useful for members of the Drew Lab at PSU, and unlikely to be helpful for setups outside of this lab.

The Arduino codes alterate between 2- and 3-wavelength excitation setups, dependent on the excitation bands needed. I almost exclusively used 2-channel wavelengths.

## 1. _PCO_ball_puff_pupil_FLIR_trig_
The main VI is within the '_main_' folder (_PCO_ball_puff_pupil_FLIR_trig_2024_JMR.vi_).
Meant to record headfixed mice locomoting freely on a ball.

## 2. _PCO_squeeze_puff_pupil_FLIR_trig_
The main VI is within the '_main_' folder (_PCO_squeeze_puff_pupil_FLIR_trig_2024_JMR.vi_).
Meant to record headfixed, anesthetized mice undergoing mechanical compression of the abdomen.

## 3. _PCO_whisker_puff_pupil_FLIR_trig_
The main VI is within the '_main_' folder (_PCO_whisker_puff_pupil_FLIR_trig_2024_JMR.vi_).
This was the first adaptation of package 1. Unlike package 1, this does not feature offsets between combined whisker stim and abdominal compressions, but does feature selection between left and right whisker stimulation.
