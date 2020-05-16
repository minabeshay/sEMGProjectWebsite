# Project Overview
Our project is a pre-processing procedure to better actuate a prosthetic arm using muscle signals from the forearm of a patient with the use of Surface Electromyography (sEMG) sensors. Our work experiments with wavelet transform theory as a means of pre-processing for sEMG signals. By first performing a wavelet transform on the sEMG signals, we found that we can greatly improve classifier accuracy to gain more performance from the typically noisy sEMG data.


## Real World Applications

We wouldlike to setup a system that can provide accurate classification results from the muscle signals in real time. This would benefit many prostheses applications as well as diagnostics on muscle related disorders.

Our biggest desire after real-time functionality is to expand our testing to more hand motions to see how the wavelet transform affects the classification of a more varied data set. Since the same arm muscle can receive many different actuation signals to perform the variety of motions our hands achieve, it would be interesting to see how well our algorithm can still classify motions that activate similar muscle groups. The other change we would like to try is experimenting with the positioning and quantity of the sEMG Sensors. While we used a ring around the muscle region we knew would be very active, we believe with more research or the assistance of a medical professional we can optimize sensor placement to use less noise sensitive locations that still provide us with the readings we need.


### Circuit Diagram

<img src= "/Circuit Diagram.PNG" width="500" style="display: block; margin: auto;" />

### Collecting Data from Front Arm

<img src= "/Real Sensors.png" width="500" style="display: block; margin: auto;" />

### Closed Fist Signal

<img src= "/raw closed fist.png" width="500" style="display: block; margin: auto;" />

### Open Palm Signal

<img src= "/raw open palm.png" width="500" style="display: block; margin: auto;" />

### Sensor Places
<img src= "/sensorPlace.001.jpeg" width="500" style="display: block; margin: auto;" />




