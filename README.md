
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
-Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter module takes the input signal in electrical form and then transforms it into optical (light) energy containing the same information. The optical fiber is the medium which takes the energy to the receiver. At the receiver light is converted back into electrical form with the same pattern as originally fed to the transmitter.

TRANSMITTER:
Fiber Optic transmitters are typically composed of a buffer, driver and Optical Source. The buffer electronics provides both an electrical connection and isolation between the transmitter and the electrical system supplying the data. The driver electronics provides electrical power to the Optical source in a fashion that duplicates the pattern of data being fed to the transmitter. Finally the optical source (LED) converts the electrical current to light energy with the same pattern. The LED SFH450V (950nm) supplied with this kit operates outside the visible light spectrum. Its Optical output is centered at near infrared wavelength of 950nm. The LED SFH756V (660nm) supplied with this kit operates at the visible light spectrum. Its Optical output is centered at wavelength of 660nm.

RECEIVER:
The function of the receiver is to convert the optical energy into electrical form, which is then conditioned to reproduce the transmitted electrical signal in it's original form. The detector SFH350V (Photo Transistor Detector) used in the kit has a transistor type output. The parameters usually considered in the case of detector are it's responsivity at peak wavelength and response time. SFH350V (Photo Transistor Detector) has responsivity of about 0.8mA/10uW at 660nm. But its response time is quite large and thus has lower bandwidth of about 300 KHz. When optical signal falls on the base of the transistor detector, proportional

current flows through its emitter generating the voltage across the resistance connected between emitter and ground. This voltage is the duplication of the transmitted electrical signal, which can be amplified.

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).
 <img width="548" height="234" alt="image" src="https://github.com/user-attachments/assets/251ab3ec-66c3-48d5-9397-2263f47cd39d" />
Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.
<img width="595" height="241" alt="image" src="https://github.com/user-attachments/assets/621c98c7-cbbd-46a4-a24b-7c4b5828f6ed" />
To measure the analog bandwidths of the phototransistor vary the input signal frequency and observe the detected signal at various frequencies.
Plot the detected signal against applied signal frequency and from the plot determine the 3dB down frequency.
Keep switch SW9 towards TX2 position.
Keep Jumper JP7 towards +12V position.
Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
Observe the detected signal at post ANALOG OUT on oscilloscope.
<img width="577" height="234" alt="image" src="https://github.com/user-attachments/assets/53e55f1e-c905-4dfa-89eb-5ece9112d9d9" />


 

---

## BLOCK DIAGRAM

<img width="969" height="570" alt="image" src="https://github.com/user-attachments/assets/b7501379-96b2-44b6-b519-79b190477256" />

---


## TABULATION  
**Transmission through Analog Link**

![WhatsApp Image 2025-11-23 at 21 46 27_4cdd111b](https://github.com/user-attachments/assets/313c48ac-0110-4433-94d7-729dca87f3fb)




---

## MODEL GRAPH

<img width="946" height="438" alt="image" src="https://github.com/user-attachments/assets/b633cee5-0476-4f61-8f73-8096928e9a5e" />

---

## GRAPH

![WhatsApp Image 2025-11-23 at 21 46 28_ced94255](https://github.com/user-attachments/assets/e1c41a2b-61d0-4664-a7bb-73e5457b95f6)


---
## RESULT

The frequency response of phototransister detector in the 600nm and 950nm fiber analog link was stuided and the retain between input and received signal was verified.
