# LysoModel
Hello, world!

In the attachment there are the program files for modeling lysosomal stresses.

There are 3 ways to use LysoModel
I. Run "Single stresses.ipynb" with flux_psi.mat, kflux.mat, naflux_psi.mat in one folder.

"Single stresses.ipynb" does simulation of individual stresses and allow for flexible configuration.
Python enviroment is required.

II. Run "LysoModel.py" file with flux_psi.mat, kflux.mat, naflux_psi.mat in one folder.

The LysoModel.py file provides access to interactive management  of initial conditions, modeling and stress activation.
Python enviroment is required. After compilation, Dash application could be started in the browser by the link http://127.0.0.1:8053/ (local host). 
The application does not need internet connection.

III. Run LysoModel.exe

To run the interactive version on your computer, download the LysoModel.exe file by link: https://drive.google.com/drive/folders/1a751gx_1D81xfGhoi1ZeNJIA4QH3z7Rl?usp=sharing 
The application do not need the internet connection and python environment. 

Dash-based software LysoModel.py or LysoModel.exe gives user ability to 
1. choose plot type: 
Ions concentration
Water flux and radius
pH and potential
single vATPase activity

2. change initial lysosomal pH, [K+], [Na+], [Cl-] and look on time response of pH, membrane potential, [K+], [Na+], [Cl-], water flux and organelle radius, vATPase activity. 

3. One could perform such monitoring in norm, or in stress conditions, switched on in short time interval from 300s to 350s: swelling (increased water flux), permeabilization, vATPase inhibition, proton efflux, described in Table 1. 
Proton sponge conditions applied from beginning of simulation. 

4. Not only one stress could be applied. 

5. Software allows user to 
switch off some curves by clicking on them in the legend, move plots (pan button on top right button panel), 
re-scale plots (Zoom button or left click rectangle selection), 
unscale (double left click or Zoom Out, Autoscale), 
save plots in .png file (to increase resolution print to .pdf file with desired DPI). 
Crosshair tool provide values for X and Y coordinates on selected curve. 

6. To reset all parameters to pre-set values just refresh browser page (F5 or refresh button in the browser).

NB: To avoid LysoModel crash (errors will occur and software won't respond), please do not change any parameter while application is on "Updating" process after previous change. "Updating" status is written on the name of the browser tab.

Take care of yourself.
