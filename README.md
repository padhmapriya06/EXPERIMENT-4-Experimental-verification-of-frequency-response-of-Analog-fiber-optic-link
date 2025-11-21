
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
---

<img width="1280" height="1003" alt="image" src="https://github.com/user-attachments/assets/9828f707-63f1-4b05-bd27-16982eb5f70f" />

---

## TABULATION  
**Transmission through Analog Link**

<img width="1280" height="1255" alt="image" src="https://github.com/user-attachments/assets/35e7b821-b8b0-414c-aec3-91e47af2f5f6" />

---

## MODEL GRAPH

<img width="1040" height="800" alt="image" src="https://github.com/user-attachments/assets/50e61008-4ebc-49ef-84a8-86f91957d059" />

---

## RESULT
Thus the 660nm & 950 nm Fiber Analog Link and the Frequency response of the phototransistor detector studied and plotted input signal & received signal
