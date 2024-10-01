## PSI3214 Electrical Instrumentation Laboratory - Microphone-Based Musical Instrument Tuner
# Project Overview
This project is part of the PSI3214 Electrical Instrumentation Laboratory course and involves designing a musical instrument tuner. The system consists of a microphone connected to an Arduino, which digitizes the analog audio signal. The digitized signal is then sent to a computer and processed using LabVIEW, where a Fourier Transform is applied to analyze the frequency components and determine the corresponding musical note.

# Objectives
Capture sound from a microphone and convert the analog signal to digital using Arduino.
Transmit the digitized signal to a computer for further processing.
Utilize LabVIEW to apply a Fast Fourier Transform (FFT) to the signal.
Identify the fundamental frequency of the sound and determine the corresponding musical note.
Display the musical note to create a functional instrument tuner.

# Hardware Components
Microphone: Captures the analog sound signal.
Arduino: Digitizes the signal from the microphone using its ADC (Analog-to-Digital Converter) and sends it to the computer via serial communication.
Computer: Receives the digitized signal and runs the LabVIEW application to process it.
Software Components
Arduino IDE: Used to write and upload the code for sampling the microphone input and sending it to the computer.
LabVIEW: The digital instrument used to perform Fourier Transform on the sampled data and determine the musical note based on frequency analysis.

# How It Works
Microphone Input: The microphone picks up the sound signal, which is an analog waveform.
Analog to Digital Conversion (ADC): The Arduino samples the analog waveform at a specific rate and converts it to a digital signal.
Signal Transmission: The Arduino sends the digitized signal to the computer via serial communication.
Fourier Transform in LabVIEW: The digital signal is processed in LabVIEW, where a Fast Fourier Transform is applied to find the fundamental frequency of the sound.
Musical Note Detection: The fundamental frequency is matched to the nearest musical note (e.g., A, B, C, etc.), and the corresponding note is displayed, making the system function as a musical instrument tuner.

# Results
The system successfully identifies musical notes by analyzing the frequency content of audio signals in real-time. This project provides a practical example of using electrical instrumentation and signal processing techniques to solve real-world problems.

# Usage
Connect the microphone to the Arduino and ensure proper connections for analog signal input.
Upload the Arduino code using the Arduino IDE to digitize the signal and send it to the computer.
Open the LabVIEW instrument, run the VI (Virtual Instrument), and observe the detected frequency and corresponding musical note.
