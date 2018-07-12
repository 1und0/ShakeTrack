# ShakeTrack
Acceleration data of 90 handshakes, recorded with motion sensors at the wrist and at the finger. During the acquisition process, 60 people participated in pairs of two. Consequently, the dataset consists of 30 unique pairings. To reduce the impact of outliers each pairing contributed three handshakes.

The measuring units were built out of two IMUs (BNO055) to measure the acceleration, one
microcontroller (nrF52) to route the data and an Android device (Nexus5) to start and stop the measurements and to store the results. The overall mean sampling rate of our data collection setup was 66.4 Hz.

# Notes
* Finger sensor data is denoted with an *"A"* (1A.csv) in the filename
* Wrist sensor data is denoted with a *"B"* (1B.csv) in the filename
