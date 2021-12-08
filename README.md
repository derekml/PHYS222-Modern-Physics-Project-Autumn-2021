# PHYS222-Programming-Project-Autumn-2021
Names: Derek Lee, Davi Lazoritz

Project: Data visualizer
Goal: Using a given dataset of atomic spectra lines, visualize the wavelengths that are within the visible spectrum.

Data file source: NIST Atomic Spectra Database
URL:  https://physics.nist.gov/PhysRefData/ASD/lines_form.html

Instructions for downloading dataset:
Visit URL above.
Then, follow the steps in the image below to get the desired dataset.
In field 1, input the desired atom ('H' for hydrogen is recommended).
Click box 2 to view other settings.
Make sure the other fields in red are selected.
Finally, click the last box "Retreive Data".
Save the file as ".csv" in the same directory as the Jupyter notebook file, any name.
[IMG]

In the Jupyter notebook, run the first code cell to import packages required.
In the second cell, edit the first line to specify the filename that you chose above. Then run the rest of the code.

In the output, the figure is interactive where you can hover the cursor to view coordinates in the figure at the bottom right corner.
The legend can be dragged and moved around. The interactions may be laggy.
Click the "power" button at the top right corner to stop the interactive figure.
