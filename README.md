# AUDIO-AMPLIFER-USING-A-MOSFET
ABSTRACT:
MOSFET is a three terminal semiconductor device which is mainly used in small signal amplifiers because its input impedance is extremely high.So it can be easily biased from a Dc supply. When we apply a small Ac signal it is superimposed on this Dc bias at the gate terminal, then the MOSFET will act as an amplifier. So, we will see how a MOSFET is used to amplify an audio signal.
BASIC IDEA ON AUDIO AMPLIFIER AND ITS USES:
 An Audio amplifier is a device, which is a capable of strengthening the week signals to drive the speaker.
 Any electronic device that increases the power of an electrical signal whose vibrations are confined to the audio frequency range, the range that can be perceived by the human ear is an audio amplifier.
 All devices that transmit, record, or otherwise electronically process voice signals employ audio amplifiers.
 Voice-recognition or voice-synthesis systems, communications or eavesdropping devices, hearing aids, entertainment systems, talking toys, are examples of devices containing audio amplifiers.
CIRCUIT DIAGRAM:
![image](https://user-images.githubusercontent.com/104260487/170631544-b137b65c-aa3f-4079-b43b-731c103d08aa.png)
WORKING:
 The diagram shown here is of a 10W MOSFET audio amplifier circuit that requires only a single supply.
 The circuit works on the basic concept of transistors.
 Low-frequency audio signals are provided from some devices.
 Single rail supply is seldom used in Class-B power amplifiers. Anyway, for low power applications like this, it’s quite fine.
 Transistors BC107 are wired as a Darlington pair works as the preamplifier.
 Preset 4.7K Resistor controls the quiescent current while 560k resistor provides feedback.
 The output is coupled to a speaker through 2200uF capacitor.
 220 uf Capacitor is the power supply filter and 1uF is the input DC decoupling capacitor.
 From this, the small signals will be amplified. And the bandwidth will be increased. Now We can hear the loud sound from the speaker.
OUTPUT:
YELLOW LINE IS OUTPUT (AMPLIFIED ONE)
BLUE LINE IS INPUT (WAVE FILE)
![image](https://user-images.githubusercontent.com/104260487/170631845-bc1778aa-e02f-40b1-b8e6-853a6b7a88b9.png)
