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

<img width="889" height="452" alt="image" src="https://github.com/user-attachments/assets/61e34b77-2c24-470e-b303-522c0612ed02" />

## OUTPUT GRAPH:

## SIGNAL OUTPUT(WITHOUT FILTER)

<img width="898" height="472" alt="image" src="https://github.com/user-attachments/assets/20f1f9fe-2577-4d78-8dcb-a2c6153bc5ca" />

## SIGNAL OUTPUT(WITH FILTER)

<img width="895" height="455" alt="image" src="https://github.com/user-attachments/assets/e91a7804-70c0-44a7-940f-f3f6e7249a76" />

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
