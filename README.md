# DC-DC-resonant-buck-converter
2020 remote summer project under Dr. Mainak Sengupta, IIEST Shibpur.  
12 V to 5 V, 200 kHz, 50 W DC-DC resonant buck converter - both ZCS and ZVS topologies. Output current = 10 A.
In this project I had designed the power circuit, gate driver,closed loop voltage mode control, as well as the output filter inductor. 

This repository contains the Altium Designer PCB design files, PSIM resonance simulation files.
MOSFET used - IRF640N
At first I designed a BJT based totem-pole gate driver circuit, but since my switching frequency is 200 kHz, I decided to use UCC5304 Gate driver IC from Texas Instruments. It indeed made the design a little less clumsy!
I thoroughly enjoyed (and got frustrated at times!) designing my very first power supply (and PCB)!
Softwares used: Altium Designer 18, PSIM, SEQUEL (IIT Bombay Circuit simulator), MATLAB/Simulink, LtSpice.
I am grateful to have had the opportunity to learn from then graduate student Kousik Ghosh (now pursuing Ph.D at IIT Madras) and Ph.D candidate Abhishek Kar. Without their patient hearing of my silliest doubts, I would not have been able to succeed in this project.
