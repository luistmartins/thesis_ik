Industrial Kitchen Energy Management

This repository contains the code, datasets, and figures developed by Luís Martins (ist1112233) as part of his Master’s thesis on energy management and demand-side flexibility in industrial kitchens, developed within the SENCY project.

The work focuses on data-driven appliance characterization, day-ahead flexibility planning, and real-time energy management, considering different optimization objectives.

Repository Structure

thesis_ik/
├── Code/
│   ├── characterization.ipynb
│   ├── Day_Ahead_Plan_Max_Utility.ipynb
│   ├── Day_Ahead_Plan_Min_Consumption.ipynb
│   ├── Day_Ahead_Plan_Min_Cost.ipynb
│   └── Real_Time_Control.ipynb
├── Data/
├── Figures/
│   ├── Bckg/
│   ├── DrawIO_Thesis_LM/
│   ├── Images_Thesis_LM/
│   ├── Methodology/
│   └── Results/
├── .gitignore
└── README.md

Code

The Code/ directory contains the Jupyter notebooks implementing the proposed methodology.

Notebook	Description
characterization.ipynb	Appliance characterization, including activation profiles, ON/OFF episodes, and flexibility weights.
Day_Ahead_Plan_Min_Cost.ipynb	Day-ahead planning to minimize electricity costs, integrated with real-time control.
Day_Ahead_Plan_Min_Consumption.ipynb	Day-ahead planning to minimize energy consumption, integrated with real-time control.
Day_Ahead_Plan_Max_Utility.ipynb	Day-ahead planning to maximize appliance utility, integrated with real-time control and an optional block-size comparison.
Real_Time_Control.ipynb	Standalone real-time control for utility maximization and energy consumption minimization, including flexibility analysis.

Data

The Data/ directory contains the datasets used for appliance characterization and energy management.

The datasets include:

* CSV files containing appliance activation profiles.
* Excel files containing additional appliance information and activation data.

These files are used as inputs for the characterization, planning, and real-time control methodologies.

Figures

The Figures/ directory contains the diagrams and figures developed for the thesis.

Directory	Description
Bckg/	Background figures related to demand-side management and energy management concepts.
DrawIO_Thesis_LM/	Editable Draw.io diagrams used throughout the thesis.
Images_Thesis_LM/	Additional images developed for the thesis.
Methodology/	Figures illustrating the proposed methodology and optimization models.
Results/	Figures presenting the results of the characterization, planning, and real-time control methodologies.

Requirements

The notebooks require Python and Jupyter, along with the following dependencies:

* NumPy
* pandas
* Matplotlib
* openpyxl
* Pyomo
* HiGHS (highspy)
* IPython

Execution

Clone the repository and open the notebooks from the Code/ directory.

The notebooks use the datasets stored in ../Data/. Each notebook can be executed independently by running its cells sequentially.

The day-ahead planning notebooks include the corresponding real-time control implementation. Cross-strategy comparisons execute the relevant planning sections of other notebooks in memory.

Plots and results are displayed directly in the notebooks without automatic file exports.

Author

Luís Martins
Student ID: ist1112233
Master’s Thesis — Industrial Kitchen Energy Management
SENCY Project
