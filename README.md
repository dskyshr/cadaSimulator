# googleColab-cadaSimulator
"cadaSimulator" is a simulator to calculate the ex-post consumption rate (= ex-ante match size/the number of all capacities) for CADA algorithm. This simulator is expected to be run on the enviroment of Google Colab. The consumption rates of DA-STB and DA-MTB will be derived simultaneously. After calculating consumption rate, the graph to compare above 3 ways will be drawn.
# DEMO
# Features
# Requirement
Google Colab enviroment or other Python3 enviroment.
# Installation
"!git clone https://github.com/dskyshr/cadaSimulator.git" on the execution environment of Google Colab.  
If you want to use on other Python enviroment, conver .ipynb files .py files after downloading the contents in this repository.
# Usage
1. Verify that my_module.ipynb is placed the same directory as CADA_simulation_3.ipynb. 
1. Change the parameters required (num_school, num_capacity, num_student, alpha) depend on your requirments. alpha is needed to be in interaval [0,1].
1. Basically, execute the run blocks from the top of CADA_simulation_3.ipynb.
# NOTE
The producer did not test under other python enviroment.
# License
This software is under GPL license.
