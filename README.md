# XJTU-Ball-Screw-Degradation-Dataset
This release provides the friction torque degradation data and the corresponding current signal data collected during the ball screw performance degradation experiments.

The tested ball screw has a lead of 8 mm, an accuracy grade of P2, a rated dynamic load of 16,400 N, and a preload of 1,500 N. Throughout the experiment, the external load was kept constant at 1,000 N.

A variable-speed loading scheme was adopted to simulate degradation under different operating conditions. The rotational speed was initially set to 300 r/min and was then increased by 200 r/min after every 20 degradation tests.

The friction torque was measured after disassembly at different degradation stages. Each friction torque file contains 30 rows. The first row represents the initial state before degradation, and the subsequent rows correspond to the measurements obtained after every five degradation tests. The friction torque value represents the mean value over the travel stroke.

The current signals were measured at a rotational speed of 100 r/min with a sampling frequency of 10 kHz. Each current signal file contains 30 seconds of three-phase current data. The current signal data are provided in the release files.

These data can be used for ball screw condition monitoring, degradation analysis, health indicator construction, and remaining useful life prediction.

