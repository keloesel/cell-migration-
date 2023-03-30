# cell-migration-
MATLAB files for calculating migration metrics after tracking nuclei in TrackMate:

This script inputs .csv file from TrackMate v7 'tracks' output. It will
calculate basic migration metrics for filtered cells: average cell speed (microns/hour), average
cell accumulated distance, average cell euclidean distance, average cell, 
theta (in radians) to a csv file within the starting folder. It will read all the files within the starting file that have the same file name
pattern.
