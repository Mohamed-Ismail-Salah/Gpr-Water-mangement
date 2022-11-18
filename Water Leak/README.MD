
## Water Leakage Detection
An IoT solution which helps determine if there is a  leak and the type of leakage in a pipe using a 1-accelerometer 2-pressure 3- hydrophone and those sensors were applied on both looped & Branched network architecture.
There are times when a pipe breaks and lakhs of litres are wasted then and there. It becomes difficult to detect leakages beforehand and try to take proper action accordingly. Even in homes, the leakage occurs at one point in the water system, but the actual issue is because of another point in the system.
There definitely exist a sense of realisation to save and preserve pure and potable water for future use.
If such leakages go undetected and predominant then the above is not possible



## data summary

This dataset includes two hundred and eighty signals acquired from a laboratory-scaled 
water distribution testbed with four types of induced leaks. Leaks were induced in a laboratory scaled water distribution system with 152.4 mm (6 in.) diameter PVC pipes. Three sensor 
types_accelerometer, hydrophone, and dynamic pressure transducer_two sensors of each kind 
were employed to measure acceleration, acoustic, and dynamic pressure data. The sensor data 
were recorded through controlled experiments where the following were changed: network 
architecture, leak type, water demand flow, background sound, and sensor locations. Each sensor 
signal was recorded for 30 seconds. Network architectures were Looped (LO) and Branched (BR). 
Leak types were Longitidinal Crask (LC), Circumferential Crack (CC), Gasket Leak (GL), Orifice 
Leak (OL), and Nonleak (NL). Water demands were 0.18 and 0.47 L/s, and Transient (the flow 
rate abruptly changed from 0.47 L/s to 0 L/s). Background sound (S vs. NS) determines if there 
was ambient sound during acoustic data measurements. Finally, sensor location represents 
variations of sensor locations throughout the testbed. Accelerometer and dynamic pressure 
transducer data are in .CSV format. Also, hydrophone data are in .RAW format with 8000 Hz 
frequency and can be converted to other formats via Audacity software.

![image](https://user-images.githubusercontent.com/31762490/202792094-83c4967c-66ce-4011-9e55-98af542d3892.png)
![image](https://user-images.githubusercontent.com/31762490/202792146-7bd5e21c-2113-4035-a4f2-a4fa5aaade5a.png)

#### The data can be downloaded from the following link:
https://data.mendeley.com/datasets/z8gxwdt5dj

## Model architecture
we created 6 cnn models and fine tuned each of them to detect water leakeage type if there was one

![image](https://user-images.githubusercontent.com/31762490/202792566-9dc1b184-a310-4618-82c5-bde524e97f90.png)

## model summary
![image](https://user-images.githubusercontent.com/31762490/202793082-7f883d11-8290-44b7-87a6-fb8cd81e4e87.png)

