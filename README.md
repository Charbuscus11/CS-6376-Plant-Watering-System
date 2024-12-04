# CS-6376-Plant-Watering-System

# Introduction
This project involves a Simulink model of a plant watering system designed to optimize water delivery based on environmental and plant-specific parameters. By reproducing the experiment, you can explore how the system adapts to changes in inputs such as Evapotranspiration (ETo), Plant Factor (PF), and the canopy radius (R). This guide provides step-by-step instructions to access and run the Simulink model.

# Prerequisites
Before proceeding, ensure the following requirements are met:

MATLAB with Simulink installed: Make sure you have MATLAB and Simulink installed on your system. Any version compatible with the Simulink model should work.
Simulink file: Download the provided Simulink file (*.slx).

# Instructions

Step 1: 
Install MATLAB with Simulink
If you don’t have MATLAB and Simulink installed, download and install them from the official MathWorks website. Follow the installation instructions specific to your operating system.

Step 2: 
Open the Simulink File
Launch MATLAB.
Navigate to the folder where the Simulink file is located. Use the MATLAB command window to navigate (e.g., cd 'path_to_file').
Open the Simulink file by double-clicking it or using the command:
matlab
Copy code
open_system('filename.slx');

Step 3: 
Set the Simulation Time (Optional)
The trials were conducted over a 120-second simulation period. To replicate this setup:
In the Simulink toolbar, click on the Model Configuration Parameters (gear icon).
Under the Solver tab, set the simulation stop time to 120 seconds.
Save the changes.

Step 4: 
Run the Simulation
Click the Run button (green triangle) in the Simulink toolbar to start the simulation.
During the simulation, you can adjust the gauges corresponding to ETo, PF, and R in real-time. Observe how these changes dynamically influence the water flow rate and cumulative water dispensed.

Step 5:
View Results
After the simulation ends:
Open the Scope Blocks provided in the model.
Flow Rate Scope: Displays the real-time flow rate adjustments based on your parameter changes.
Cumulative Water Dispensed Scope: Shows the total water dispensed over the simulation period.
Compare the results of your trial with different gauge settings to analyze the system's adaptability and performance.

Notes
Experiment with different gauge settings during the simulation to observe system responsiveness under varying conditions.
For troubleshooting, refer to MATLAB's Simulink documentation or the Help menu within the software.

Feedback and Support
If you encounter issues or have questions about the model, please feel free to reach out. Happy experimenting!
