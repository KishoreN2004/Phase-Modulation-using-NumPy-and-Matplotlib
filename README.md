# Phase-Modulation-using-NumPy-and-Matplotlib

### Aim
To implement and analyze phase modulation (PM) using Python's NumPy and Matplotlib libraries.   
### Apparatus Required
1.	Software: Python with NumPy and Matplotlib libraries  
2.	Hardware: Personal Computer Theory  
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike frequency modulation, where the frequency is varied, in phase modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.  

The general form of a PM signal can be represented as:


<img width="306" height="241" alt="image" src="https://github.com/user-attachments/assets/b8d2db63-afe0-4bd8-8826-efc89a111423" />

### Algorithm

1.	Initialize Parameters:  
o	Set values for carrier amplitude (AcA_cAc), carrier frequency (fcf_cfc), message frequency (fmf_mfm), sampling frequency, and phase deviation sensitivity (kpk_pkp).  
2.	Generate Time Axis:  
o	Create a time vector for the signal duration based on the sampling frequency.  
3.	Generate Message Signal:  
o	Define the message signal as a cosine wave.  
4.	Generate PM Signal:  
o	Apply the PM modulation formula to obtain the modulated signal.  
5.	Plot the Signals:   
o	Use Matplotlib to plot the message signal, carrier signal, and phase-modulated signal.  


### Program

<img width="1092" height="711" alt="Screenshot 2025-10-15 175451" src="https://github.com/user-attachments/assets/95524954-ab8f-47d2-ab46-5e0fd263629e" />
<img width="448" height="314" alt="Screenshot 2025-10-15 175815" src="https://github.com/user-attachments/assets/786c4743-152c-48a1-8f3b-592cad32187d" />


### Tabulation

![WhatsApp Image 2025-11-15 at 10 55 54_aa500d53](https://github.com/user-attachments/assets/b9d2ae25-e17f-462a-8447-8ad2647f8f3a)


### Output

<img width="915" height="906" alt="Screenshot 2025-10-23 161520" src="https://github.com/user-attachments/assets/69030bbc-2e86-4e62-b914-14a4c7ca2d66" />

### Result

The message signal, carrier signal, and phase-modulated (PM) signal will be displayed in separate plots. The modulated signal will show phase variations corresponding to the amplitude of the message signal.

