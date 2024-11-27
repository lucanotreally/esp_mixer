# esp_mixer
Analog studio mixer
An analog studio mixer, completely inspired by Elliot Sound Products website project p30.
All the channel on the mixer will be the same.
The channel has the following characteristics:
  -MIC input:
    every channel can take a standard mic input via xlr, it can handle both dyncamic microphones and condenser ones, as it has a 48V switch integrated.EVERY CHANNEL CAN TOGGLE THE 48V FOR ITSELF.
  -LINE input:
    you can have line input through xlr or standard 6.3mm jack.
  -48V PAD AND PHASE switches:
    48v switches stated above, every channel has a pad switch to attenunate LOUD signal sources, and it attenuates by 20dB, and the phase swtich inverts the phase of the balanced signal to handle phase issues with close by mics.
  -GAIN:
    every input has variable gain
  -EQ:
    the eq section has HIGH, MID and TREBLE control, with the MID frequency cut adjustable via a pot, ranging from 500Hz to 2kHz.
  -AUX:
    there are 2 Auxiliary outputs, one is set to be PRE-FADE, named AUX1, while AUX2 can be toggled as PRE or POST-FADE, via his own switch. Each AUX out has its volume knob.
  -PAN:
    a pan knob, to decide how much of the signal has to be sent LEFT or RIGHT.
  -FADERS:
    a mono fader at the end of the signal chain, not relevant to the mixer circuitry, but in my build faders will still be knobs, not linear faders.
The mixer has 5 main sections:
- The input section:
  Here all the input get sorted trough the switches 
