# ampanova
This project consists of a waveform generator which can generate sine, square, triangular and quadratic waves of two different frequencies. This project also features a differential equation solver which can solve differential equations of first and second order.. It also has a set of filters to selectively modify different frequencies.  

The working of the project is as follows:  
1. Function generator  
<img width="379" height="215" alt="Screenshot 2025-08-04 191644" src="https://github.com/user-attachments/assets/4c1a7e81-a2a8-4855-9ae7-1497356b8e9e" />

The function generator produces sine waves of different frequencies. In this project, four effective function generator modules have been used, which are tuned to different frequencies. The arrangement involves    two modules creating waves of frequenices 1Hz and 2Hz, and is connected to a schmitt trigger, which transforms it into a square wave of the same frequency. An adder is present for the four outputs thus created.  
Here, Frequency1 = 1Hz, and Frequency2 = 2Hz.  
These frequency values can be altered by altering the values of the capacitances of these wein bridge oscillators.  
The function generator also features voltage controlled switches made using mosfets, which close when a high input is given, and open when a low input is given. A picture of the circuit is given below.  
<img width="1822" height="860" alt="image" src="https://github.com/user-attachments/assets/f2d4171d-d99d-4df0-9e07-1830b4bcc9e0" />   

<img width="679" height="476" alt="Screenshot 2025-08-04 191700" src="https://github.com/user-attachments/assets/a6e39f7b-1375-46ed-8304-4fcf0413e733" />   
The image of this part of the circuit is given below:  
<img width="1387" height="707" alt="image" src="https://github.com/user-attachments/assets/90c5e039-8477-4488-a65e-a1078169af0e" />  



   
