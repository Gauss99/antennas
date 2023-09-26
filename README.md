# microstrip_patch_antennas
A repository for my final project where I simulated a range of microstrip patch antennas patterns and generated different .csv files for exploratory data analysis and machine learning.

This repo contains 5 .csv generated through ANSYS 2022 where I simulated microstrip patch antennas varying different parameters, such as length, subsctract height, so on and so forth.
The values for the dieletric constants used where from existing materials, being [2.2, 3.0, 4.4, 6.15, 10.2].
The L dimension ranged from 10 mm to 40 mm, where every single resonant frequency was found for these dimensions and dieletric constants, being in total 150 different resonant frequencies.
Through these datasets, a exploratory data analysis and data cleaning was made, filling discrepant values and generating subdatasets for each L.
After it, a final dataset consisting of resonant frequencies concerning the desired mode was created, wich will be used for a Machine Learning algorithm so it can predict a resonant
frequency/physical dimension of any point in between the 1 GHz and 10 GHz range.

