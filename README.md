# PHYS222-Programming-Project-Autumn-2021
Names: Derek Lee, Davi Lazoritz

Project: Data visualizer
Goal: Using a given dataset of atomic spectra lines, visualize the wavelengths that are within the visible spectrum.

Data file source: NIST Atomic Spectra Database
URL:  https://physics.nist.gov/PhysRefData/ASD/lines_form.html

Instructions for downloading dataset:
Visit URL above.
Then, follow the steps in the image below to get the desired dataset.

[IMG]

In field 1, input the desired atom ('H' for hydrogen is recommended).
Click box 2 to view other settings.
Make sure the other fields in red are selected.
Finally, click the last box "Retrieve Data". It may load as a text file in your web browser. Right-click the page and “save-as” [on Mac, press Shift-Command-S]. Rename the file extension to “.csv”.
Save the file in the same directory as the Jupyter notebook file. 

In the Jupyter notebook, run the first code cell to import packages required.
In the second cell, edit the first line to specify the filename that you chose above. Then run the rest of the code.

In the output, the figure is interactive where you can hover the cursor to view coordinates in the figure at the bottom right corner.
The legend can be dragged and moved around. The interactions may be laggy.
Click the "power" button at the top right corner to stop the interactive figure.

What we learned:
The biggest thing that was completely new to us was how to use pandas. This included learning how to import .csv files, querying the columns of data we needed, cleaning the data to remove extra characters, converting the objects to the correct usable datatypes, querying a specific range of data to use.
We also learned how to create a complicated plot that was interactive. To plot the lines we wanted, we used a nested for-loop to place the lines in the correct bins for different colors of visible wavelengths.
For the plot, we learned how to add a legend that was draggable and a cursor pointer that shows the coordinates of a line you want to identify.
