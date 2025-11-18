
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

<img width="527" height="222" alt="4" src="https://github.com/user-attachments/assets/e04a34d5-b351-4901-85a9-09bc420e50b8" />


---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**
<img width="571" height="122" alt="44" src="https://github.com/user-attachments/assets/8f94d1ce-f929-416d-84fb-ce1606bc5d79" />



## TABULATION  
**Transmission through Analog Link**

![444](https://github.com/user-attachments/assets/12294d2a-68f0-46c8-8323-428714d9dbb7)


## MODEL GRAPH

<img width="721" height="308" alt="4444" src="https://github.com/user-attachments/assets/84bbf25d-35d9-4dd9-a47e-4ae4330c76ba" />

![WhatsApp Image 2025-11-18 at 10 56 08_b212c0c6](https://github.com/user-attachments/assets/1e77141c-680a-4884-a320-5296a607b66a)



## RESULT

The transmitted and received waveforms for the 660 nm fiber link matched closely, confirming faithful analog and digital signal transfer. Output amplitude decreased with increasing frequency, showing the fiber link’s frequency-dependent response. The calculated –3 dB point confirms the bandwidth of the 660 nm analog/digital fiber optic link.
