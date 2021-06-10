# FM Bugger Circuit

## Problem Statement
Designing a transmitter which can transmit frequency modulated audio signal which can be detected by an ordinary FM Radio.

## Ideation and Pipeline
* Capturing sound and removing noise -> Frequency Modulation -> Transmission

| Part of the Pipeline | Feasibility | Advantages | Disadvantages |
|----------------------|-------------|------------|---------------|
| **Capturing sound and**<br>**removing noise** | Using mic and<br>few capacitors | Components can be easily<br>found | Low quality of mic can<br>cause problems |
| Amplifying and<br>frequency modulating signal | Using transistors<br>and tank circuit | Works for even low voltage<br>like 3V | Choosing values makes the<br>task little difficult |
| **Transmitting signal** | Using Antenna | Variety of options available | battery voltage and circuit gets<br>changed accordingly |

## Choosing pipeline
Here we can make betterments in Capturing sound and removing noise, Transmitting signal.

Capturing sound and removing noise is being done by mic and capacitors placed. Position and value of capacitors are important for removal of noise. Capturing sound depends on quality of mic. They had prefered to use a condenser microphone but for better clarity we can use a dynamic microphone.

Signal transmission is being done by antenna which should be around 1/4th of wavelength of wave. Here, frequency of transmission is set by capacitor in tank circuit. Capacitor is set accordingly to get a frequency in range of 88 to 108MHz. Distance of propagation can be determined by voltage and few changes in circuit for distance for shorter 3V battery is sufficient, whereas for longer distances 5V battery is need.

Better avoid metal casing for the circuit as it may effect FM signals. 


# Security access using RFID reader

## Problem Statement
Designing a security lock system which can be accessed by a RFID tag/card.

## Ideation and Pipeline
* Scanning RFID ->  Microcontroller 

| Part of the Pipeline | Feasibility | Advantages | Disadvantages |
|----------------------|-------------|------------|---------------|
| Scanning RFID        | working libraries available | Low power consumption |  |
| Microcontroller      | Experience needed | Easily Programmable | Hard for beginners |

## Choosing pipeline
