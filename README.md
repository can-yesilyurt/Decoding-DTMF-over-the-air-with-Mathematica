# Decoding-DTMF-over-the-air-with-Mathematica
Dual Tone Multi Frequency (DTMF) - Signal Identification using Wolfram Mathematica

DTMF Decoder

1) Choose the audio-input-device which can be:
   
   a) just the microphone of the PC/laptop or any external micrpphone
      In that case, the code captures and decodes (e.g.) mobile-phone dial tones over the air.
      
   b) output of a software defined radio application such as Gqrx SDR or CubicSDR
      The audio output of the SDR application is required to be set as a virtual audio input device. 

2) After coosing the device, click "OK" button to run the rest of the code and let the visual part appears.

3) Click start button, which activates the input device and start real-time processing.

4) Test by dialing a number with a mobile phone and it should be captured and displayed realtime dynamically.
