# My-run-of-Quantum-Simulation-of-GUT-Baryogenesis
This includes my run for "Quantum Simulation of GUT Baryogenesis"  provided by IBM's Qiskit Global Summer School (QGSS) 2025 community labs. Credit for the original creation of this notebook belongs to Mukul Kamar and Vivek Pal.

The changes I made to this notebook included running the quantum circuits on ibm_kingston instead of ibm_sherbrooke, executing my circuits using Batch instead of Session, and adding the code needed to attempt task 1 described at the end of the notebook. 

What I learned:
1) Understood the theoretical foundation of GUT baryogenesis
2) Implement quantum circuits to simulate particle decay processes
3) Explore the role of CP violation in matter-antimatter asymmetry
4) Solve the Boltzmann equations for cosmological evolution
5) Run experiments on real quantum hardware
6) Compare simulation results with theoretical predictions

Installation & Usage: To open this up, I used Ubuntu to create a Python environment. This was done by opening Ubuntu and placing the following commands:

python3 -m venv venv 
source venv/bin/activate 
jupyter lab --no-browser --ip=0.0.0.0 --port [insert a port number] 
To run this, however, you may need to create a new runtime service, as this was designed to be for participants in the summer school program.

To create a service to run on quantum hardware, be sure to implement the following code with at least this much information at the beginning of your cells: 
QiskitRuntimeService.save_account( channel="insert appropriate channel", token='insert API key', instance="insert CRN number", overwrite=True )
