# Aim: 
Measurement of Displacement using LVDT
## Objective:-
Study the relation between core displacement and output of LVDT
Understand the effect of change in supply frequency on LVDT performance
Understand the effect of change in excitation (supply) voltage on LVDT performance.

## Procedure:
First you need to configure the LVDT. Click on ' Show panel' tab at the right bottom For making the circuit, drag and drop the primary coil, Armature and secondary coils at the loactions shown on left hand side.
Now select No of Turns, peak to peak supply volatge and frequency from the drag and drop menu, available below LVDT diagram. Click on configure block to configure LVDT.
Now click on the black rectangular core placed between primary and secondary windings.
Drag the core to left hand side and observe the effect on the output magnitude. This can be observed on the time vs output volatge waveform and on the Distance vs output voltage graph. The core displacement is indicated in the square box below the diagram
Drag the core to right hand side and observe the effect on the output magnitude. Also observe the change in the phase.
Repeat steps 2 to 4 by changing supply volatge keeping frequency and no of turns constant.
Study the effect on the output voltage. For this click on blue color 'Configure' tab in the right side panel. You need to select required parameter value from drop down menu. After selecting the values click on green ' Configure' tab to set the parameter values.
Repeat steps 2 to 4 by changing supply frequency keeping and no of turns constant. Study the effect on the output voltage. Now keep supply voltage and frequency constant. Change the no of turns and observe the effect on the output voltage by repeating steps 2 to 4.

## Circuit Diagram of LVDT
<img width="398" height="711" alt="WhatsApp Image 2026-05-22 at 10 49 43 AM" src="https://github.com/user-attachments/assets/779c0b41-09c4-4d1b-99bd-31103af61125" />

## NOTE
The Supply Voltage range is 5V to 15V
The Supply Frequency range is 1KHz to 10KHz
For simulation purpuse ,the Supply Voltage is restricted to 10V and Supply Frequency is restricted to 5 KHz

## Measuremnt:
Number of Turns : 1000
Supply Voltage : 5
Supply Frequency : 1000


## Formula Used :
Vout=fIp(4πNpNsµ0bx/3mlog(ro/ri))(1-(x2/2b2))
Where,
f =supply frequency (user selectable)

Ip=primary current = Vin/R

Where Vin (Vrms) is user selectable and R is the coil resistance ( 10 K Ohm)

Np=number of primary turns (user selectable)

Ns=number of secondary turns ( half of primary turns)

ro/ri=Ratio of outer and inner radii of the coil system ( = 2)

x=displacement of the core form null (from actual core postion)

µ0=permeability of space (4π10^-7h/m)

b = length of primary winding (= 20mm)

m = length of secondary winding (= 10 mm)


## Output waveforms:

<img width="1600" height="767" alt="WhatsApp Image 2026-05-22 at 10 48 49 AM" src="https://github.com/user-attachments/assets/647b503a-9237-4f14-8022-d5778bb8437b" />


## Result:
The displacement of the movable core was successfully measured using the linear variable differential transformer.


