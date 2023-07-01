# Confused-Student-EEG-Detection
This work is done to detect if a student is confused or not while watching MOOC videos from EEG signal.


These data are collected from ten students, each watching ten videos. Therefore, it can be seen as only 100 data points for these 12000+ rows.
If you look at this way, then each data point consists of 120+ rows, which is sampled every 0.5 seconds (so each data point is a one minute video).
Signals with higher frequency are reported as the mean value during each 0.5 second.


EEG_data.csv: Contains the EEG data recorded from 10 students

demographic.csv: Contains demographic information for each student

