
# Reg. No: 212222060205
# Name: Sabarisun S

Exp 5 Experimental verification of frequency response of Digital fiber optic link

# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

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
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---


## BLOCK DIAGRAM

*(Insert block diagram here)*

---

## CONNECTION DIAGRAM  
**Setting up a Digital Link**

![WhatsApp Image 2025-11-17 at 17 02 21_141772cf](https://github.com/user-attachments/assets/17e7ca1f-287e-438e-afe4-21c84d5c1e03)


---

## TABULATION  
**Transmission through Digital Link**
![WhatsApp Image 2025-11-17 at 17 03 09_0637ef60](https://github.com/user-attachments/assets/44f00407-be73-4f15-9a03-bbb94b93532f)


---

## MODEL GRAPH

![WhatsApp Image 2025-11-17 at 17 04 01_8b9c2fbd](https://github.com/user-attachments/assets/2ffdc398-3dc5-4c19-9f03-9a473795a2f9)


---

## GRAPH
![WhatsApp Image 2025-11-17 at 17 02 42_b2b181e5](https://github.com/user-attachments/assets/41162489-edfe-4dfb-a601-e6f33156bdda)

## RESULT
Thus the experimental verification of frequency response of digital fibre optic link was successfully.

