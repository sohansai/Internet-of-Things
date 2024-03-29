# IoT ECG (Electrocardiogram) System

## Aim

The aim of this project is to design and implement an IoT-based Electrocardiogram (ECG) system for recording the heart's electrical activity. The system utilizes an ECG module (AD8232) connected to an Arduino Uno, allowing the recording of the electrical signals produced by the heart and visualizing the ECG waveform through a graphical representation.

## Procedure

The EKG or ECG (Electrocardiogram) is a non-invasive diagnostic test that assesses heart rhythm and function through a recording of the electrical activity of the heart that occurs with each heartbeat. This electrical activity is recorded from the patient’s body surface and is drawn on a paper using a graphical representation or tracing, where different waves are observed that represent the electrical stimuli of the atria and ventricles. The device with which the electrocardiogram is obtained is called an electrocardiograph.

The normal rhythm of an ECG is formed by a P wave, a QRS complex and a T wave. To interpret an electrocardiogram, the presence of these waves, their shape and duration, as well as the ST segment (time that elapses between the end of depolarization and the beginning of repolarization of the ventricles, measures less than 1 mm, if it is greater than 1 mm it indicates infarction or ischemia).

The P waves allow us to know the time between the heartbeats, it is represented as a straight line between the lowest and the highest point. The T wave represents the small perceptible beat after the first and marks the end of the heartbeat. The time elapsed between one and the other must be fairly regular throughout the entire test, if on the contrary, during the test we see that the elapsed time is variable, this indicates an irregularity in the heartbeat.
Connect the A0 to OUTPUT in the module , LO- to 11 pin in arduino , LO+ to 10 pin in arduino. Upload code and check the graph in Serial Plotter.


## Understanding the ECG

The ECG or EKG (Electrocardiogram) is a non-invasive diagnostic test that records the heart's electrical activity. The normal ECG rhythm consists of a P wave, a QRS complex, and a T wave. Interpretation involves analyzing the presence, shape, and duration of these waves, along with the ST segment.

- **P Wave:** Represents the time between heartbeats, shown as a straight line between the lowest and highest points.

- **QRS Complex:** Indicates the depolarization of the ventricles.

- **T Wave:** Represents the small perceptible beat after the QRS complex, marking the end of the heartbeat.

Irregularities in the elapsed time between heartbeats or abnormalities in wave shapes may indicate heart irregularities.

#### Understanding Graphical Diagram of ECG at Serial Plotter
![image](https://github.com/sohansai/internet-of-things/assets/76840110/3d9a51a2-8c68-4e7f-90f8-c97ba252fa2e)

#### Connection Location at Limbs

![image](https://github.com/sohansai/internet-of-things/assets/76840110/757c35d6-0ddb-446d-be99-d860910765a8)


## Components

- Arduino Uno
- ECG module (AD8232)
- ECG electrodes (3 pieces)
- ECG electrode connectors (3.5 mm)
- DATA Cable
- Jumper Wires

## Circuit Diagram

![image](https://github.com/sohansai/internet-of-things/assets/76840110/54d82abe-7f91-401c-9dee-44662d7adf1d)

Note: Ensure proper connections and follow the specified pin configurations.

## Output
Output at serial plotter :

Choose : Tools -> Serial Plotter 


![image](https://github.com/sohansai/internet-of-things/assets/76840110/4d1f6bf3-5d39-479c-ae1b-185ab8160e51)
