This repository provides the description of the ball screw performance degradation dataset. The complete dataset, including the current signal data and friction torque degradation data, is available in the release files.

The tested ball screw has a lead of 8 mm, an accuracy grade of P2, a rated dynamic load of 16,400 N, and a preload of 1,500 N. Throughout the experiment, the external load was kept constant at 1,000 N.

A variable-speed loading scheme was adopted to simulate degradation under different operating conditions. The rotational speed during the degradation process was initially set to 300 r/min and was then increased by 200 r/min after every 140 hours of degradation.

After every 35 hours of degradation, the degradation process was paused and both the three-phase current signals and friction torque were measured. The current signals were measured at a rotational speed of 100 r/min with a sampling frequency of 10 kHz. Each current signal file contains 30 seconds of three-phase current data.

The degradation hour is indicated in each current signal filename; for example, Current_down_875h.txt denotes the current signal measured after 875 hours of degradation.

The files Up_FT.txt and Down_FT.txt, included in the release files, contain the friction torque degradation data of the upper ball screw and the lower ball screw, respectively. Each file contains 30 rows. The first row represents the initial state before degradation, the second row corresponds to 35 hours of degradation, the third row corresponds to 70 hours of degradation, and so on. The friction torque value represents the mean value over the travel stroke.

The current signal files and friction torque data correspond to the same degradation hours. These data can be used for ball screw condition monitoring, degradation analysis, health indicator construction, and remaining useful life prediction.
