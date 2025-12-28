# ant_maze_data
Solution attempts of the ants collectively solving different piano movers' puzzles

This folder contains CSV files with experimental trajectory data from individual attempts.
Each file includes x and y position coordinates and the orientation angle (theta) over time.
The first part of each filename is formatted as 'size_shape', where 'size' is the puzzle size (small, medium, large, extra-large) 
and 'shape' is the shape of the carried load (I, T, H, T2, H2); files of T2-trajectories start with T2 and do not include a size.
Files are grouped by puzzle size and saved in separate ZIP archives.

This folder also contains the code used to create simulated trajectories. 
To create a simulated trajectory run the main.py function. 
