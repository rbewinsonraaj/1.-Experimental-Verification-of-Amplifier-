#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-11-28 at 14 02 24_bf758ecf](https://github.com/user-attachments/assets/8f1f91c1-576a-49d8-b749-c19871062708)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-28 at 13 56 57_f58d2513](https://github.com/user-attachments/assets/a34eda4d-c587-414e-acb4-b7da06bf22db)




MODEL GRAPH 
![WhatsApp Image 2025-11-28 at 13 45 54_ffd7da14](https://github.com/user-attachments/assets/2ffd0ce4-46b6-4f66-99b2-0d99393c31a1)



DESIGN:
![WhatsApp Image 2025-11-28 at 13 55 27_d6fac75e](https://github.com/user-attachments/assets/27f55faf-165e-4d58-a887-a467113c28b4)




Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-11-28 at 14 06 09_33dd1ab2](https://github.com/user-attachments/assets/623442c5-5059-4b45-8bc2-c0bd7e916bb6)
		
 


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 14 07 13_7507b08a](https://github.com/user-attachments/assets/0025b06c-0742-4388-ae9f-d8eeaf2c2cc7)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-11-28 at 13 57 54_ffe3bfb1](https://github.com/user-attachments/assets/572043e5-02c1-494b-b337-04064007d8e5)


---

## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 13 35 10_2b833788](https://github.com/user-attachments/assets/f788159e-db07-4de3-a7df-7d9c37202031)

## DESIGN
![WhatsApp Image 2025-11-28 at 13 55 42_39b5bfd1](https://github.com/user-attachments/assets/e2178394-e8ba-4731-9eba-81e0e5695687)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-11-28 at 13 59 31_25947a1e](https://github.com/user-attachments/assets/72e08abc-9e25-4623-8a3a-f0bdc8aa511d)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 14 10 02_1f59b500](https://github.com/user-attachments/assets/75310e05-38af-4174-9ff3-ba84391f2095)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 13 48 27_f60e8066](https://github.com/user-attachments/assets/d103e729-dcd4-4451-ace7-74fd3ccb510f)




## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 13 50 04_b479640c](https://github.com/user-attachments/assets/94be0243-b486-4561-a781-9cbb15cacbd3)



---

## DESIGN
![WhatsApp Image 2025-11-28 at 13 55 55_de14490e](https://github.com/user-attachments/assets/d0d57308-138d-4e64-92bd-91b408c7c995)



### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-28 at 13 59 45_5ea8349e](https://github.com/user-attachments/assets/4d59105c-52b6-4d1c-92dd-94d736553f9b)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 14 12 53_44544c47](https://github.com/user-attachments/assets/c816cd5e-8a96-4712-9f34-1ce09a140d26)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-28 at 13 43 50_d1ca3d57](https://github.com/user-attachments/assets/3e761a4b-ddbe-416a-b9b5-05cb569b208d)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-11-28 at 14 13 55_3b561a04](https://github.com/user-attachments/assets/b95c14b8-8f22-464d-9c1b-0825689935b5)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 14 14 14_ef60efe7](https://github.com/user-attachments/assets/d1833619-f1cc-43ea-87eb-716765af5ea1)

---
## RESULT
![WhatsApp Image 2025-11-28 at 14 15 59_c979c369](https://github.com/user-attachments/assets/e1525110-84ba-4410-9522-51aa3bdb8529)
![WhatsApp Image 2025-11-28 at 14 00 49_327d2536](https://github.com/user-attachments/assets/4bbeb711-d307-4c3a-88c7-c4b0008a085e)


---
