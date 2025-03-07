# optical-IQ-modulation

Optical IQ ("In-phase" and "quadrature") modulation is a technique used in optical communication system to modulate both the phase and amplitude of an optical signal, and it is used to achieve high-speed and efficient data transmission.
This modulation method is essential for transmitting high-speed data over long distances with minimal signal degradation.<br>
<br>
Two individual I and Q optical signals are independently modulated.<br>
Optical I/Q modulator consists of two independently-controlled Mach–Zehnder interferometers (MZI) whose outputs are combined.<br>

The combining structure also includes a bias electrode that applies a phase delay between the two MZIs, allowing for the required phase control between the two modulator arms.<br>

Tx<br>
![IQ modulation1](https://user-images.githubusercontent.com/30459885/228159937-5da4aa4e-00e3-413c-a731-7c4748cfd60f.png)
![Figure_1](https://user-images.githubusercontent.com/30459885/228153151-be906128-30f4-4ce5-9949-10e73b35c671.png)

Digital Signal1<br>
Electric field of Signal1<br>
Digital Signal2<br>
Electric field of Signal2<br>
Electric field of Optical Signal (1+2)<br>
Optical Power Signal (1+2)<br>

Rx
![222](https://github.com/tacticstactics/optical-IQ-modulation/assets/30459885/8fbc7448-44f3-4d97-9479-ae09e8215572)

At Rx side, Balanced Photodetector recovers original sinals.<br>

![Figure_2](https://user-images.githubusercontent.com/30459885/228153158-7815d279-4362-49e5-b11b-44d1998c534a.png)
Electric field of Signal1(PD1)<br>
PD1 Signal<br>
Electric field of Signal2<br>
PD2 Signal<br>
Interference of of Electric field (1-2)<br>
Optical Power Signal (1-2)<br>
-> Digital Signal 1 has been demodulated.<br>

![Figure_3](https://user-images.githubusercontent.com/30459885/228153167-0a6a2506-12ac-44ec-b3ce-ec123bf8b166.png)
Electric field of Signal1(PD3)<br>
PD3 Signal<br>
Electric field of Signal4<br>
PD4 Signal<br>
Electric field of Signal2(PD4)<br>
Interference of Electric field (3-4)<br>
Optical Power Signal (3-4)<br>
-> Digital Signal 2 has been demodulated.<br>


