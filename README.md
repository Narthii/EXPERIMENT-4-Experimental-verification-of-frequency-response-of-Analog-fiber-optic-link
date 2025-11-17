
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
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

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

---

## BLOCK DIAGRAM

<img width="969" height="570" alt="image" src="https://github.com/user-attachments/assets/b7501379-96b2-44b6-b519-79b190477256" />

---


## TABULATION  
**Transmission through Analog Link**

![WhatsApp Image 2025-11-17 at 23 13 03_df7c1dfd](https://github.com/user-attachments/assets/430e5472-09b3-4819-805b-bf4ac3bb2d25)


---

## MODEL GRAPH

<img width="946" height="438" alt="image" src="https://github.com/user-attachments/assets/b633cee5-0476-4f61-8f73-8096928e9a5e" />

---

## GRAPH


![WhatsApp Image 2025-11-17 at 23 13 03_6fea0c83](https://github.com/user-attachments/assets/19f3d839-7374-4627-8351-cb62d3a64070)

---
## RESULT

The frequency response of phototransister detector in the 600nm and 950nm fiber analog link was stuided and the retain between input and received signal was verified.
