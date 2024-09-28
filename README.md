# SDR-and-AM-Receiver-Implementation


## Part 1:

### Overview
This project involves capturing RF signals using a Software Defined Radio (SDR) module and analyzing the signals in MATLAB. The project is divided into two main parts:
- Signal Capturing with SDR and GQRX
- Signal Analysis using MATLAB

### Learning Objectives:
- Capture RF signals using an SDR module
- Plot and interpret spectrum measurements

## Signal Capturing

1. **Research FM Frequency Bands**  
   Research FM radio stations in the Rochester area:

2. **SDR Setup with GQRX**  
   - Connect the SDR with the telescopic antenna to the PC.
   - Run GQRX and set the sample rate to **2.4 Msamples per second**.
   - For installation instructions, see [GQRX Tutorial](https://gqrx.dk/tag/tutorial). For Windows, download the SDR driver from the Nooelec website.
   
3. **Signal Tuning**
   - Navigate through the FM spectrum in GQRX and tune to a station listed in the table.
   - Adjust the parameters to get clear reception.
   - **Record** I/Q raw data for 4-5 seconds. Verify the recording by playback.

## Signal Analysis (Using MATLAB)

### Tasks:
1. **Plot I/Q Signals**  
   - Use MATLAB to plot the I/Q signals from the recorded data.
   
2. **Plot Magnitude Spectrum**  
   - Plot the magnitude spectrum of the recorded signal.
   
3. **Plot 1000-Point Averaged Magnitude Spectrum**  
   - Plot the average magnitude spectrum over 1000 points.
   
4. **Plot Spectrogram**  
   - Plot the spectrogram of the recorded signal.


## Part 2: AM Receiver Assignment

In this part of the project, we will build an AM receiver using MATLAB.
