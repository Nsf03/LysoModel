# LysoModel
In the attachment there are the program files for modeling lysosomal stress.

1. The .ipynb files in the "Single stress files" folder are used to simulate individual stresses and allow for more flexible configuration.
Python enviroment is required.

2. The LysoModel.py file provides access to interactive management of initial conditions, modeling and stress activation.
Python enviroment is required. After compilation, Dash application could be started in the browser by the link http://127.0.0.1:8053/ (local host). 
The application do not need internet connection.

3. To install the interactive version on your computer, download the .exe file by link: [https://drive.google.com/drive/folders/14jtxS9_WmCDpbRrqWoum-63hrtyzhsq5?usp=sharing](https://drive.google.com/drive/folders/1a751gx_1D81xfGhoi1ZeNJIA4QH3z7Rl)
The application do not need internet connection and python environment. 

Software gives user ability to change initial lysosomal pH, [K+], [Na+], [Cl-] and look on time response of pH, membrane potential, [K+], [Na+], [Cl-], water flux and organelle radius, vATPase activity. One could perform such monitoring in norm, or in stress conditions, switched on in short time interval from 300s to 350s: swelling (increased water flux), permeabilization, vATPase inhibition, proton efflux, described in Table 1. Proton sponge conditions applied from beginning of simulation. Not only one stress could be applied. 
Software allows user to scale plots (left click rectangle selection or Zoom In button on top right button panel), unscale (double left click or Zoom Out, Autoscale), save plots in .png file.
To reset all parameters to pre-set values just refresh browser page (F5 or refresh button in the browser).
