# Energy Management

| Notebook | Description |
| --- | --- |
| `Characterization.ipynb` | Device characterization: activation profiles, ON/OFF episodes, and flexibility weights. |
| `Day_Ahead_Plan_Min_Cost.ipynb` | Planning to minimize energy cost, with integrated real-time control. |
| `Day_Ahead_Plan_Min_Consumption.ipynb` | Planning to minimize energy consumption, with integrated real-time control. |
| `Day_Ahead_Plan_Max_Utility.ipynb` | Planning to maximize utility, with integrated real-time control and an optional block-size comparison. |
| `Real_Time_Control.ipynb` | Standalone real-time control: maximum utility and minimum consumption, with flexibility analysis. |

Run cells in order from `Code/`, with input data in `../Data/`. Each notebook can be run independently; cross-strategy comparisons execute the planning sections of the other notebooks in memory.

Dependencies: Jupyter/IPython, NumPy, pandas, Matplotlib, openpyxl, Pyomo, and HiGHS (`highspy`). Plots and results are displayed in the notebooks without automatic file exports.
