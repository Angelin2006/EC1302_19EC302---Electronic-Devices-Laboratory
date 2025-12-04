# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:


<img width="893" height="382" alt="image" src="https://github.com/user-attachments/assets/2944838b-3b80-43c7-a7ee-75a125b04155" />


## AC INPUT WAVEFORM:

![WhatsApp Image 2025-12-04 at 10 16 26_83f124aa](https://github.com/user-attachments/assets/e5696a1e-f44d-4b21-94bf-f800490c9201)

## OUTPUT GRAPH:

## SIGNAL OUTPUT(WITHOUT FILTER)

![WhatsApp Image 2025-12-04 at 10 16 26_85d607c7](https://github.com/user-attachments/assets/05688576-8950-4ee7-921f-2536855793ff)

## SIGNAL OUTPUT(WITH FILTER)

![WhatsApp Image 2025-12-04 at 10 16 25_9d115f24](https://github.com/user-attachments/assets/e1dc179e-015d-47e0-93eb-4e845ef6df04)

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
