[![DOI](https://zenodo.org/badge/804596288.svg)](https://zenodo.org/doi/10.5281/zenodo.11251877)
EV-Project wildfire case study

1. **Code Folder**: This folder contains all the necessary code for our project.
   - **Initialization**: Begin by initializing the car numbers at different charge levels at all nodes using "car_number_initialization_normal.ipynb" This script generates three different cases for normal charge speed. When the charging speed is halved, then we use "car_number_initialization_half_speed.ipynb" to initialize the car numbers at different charge levels at different nodes.
   - **Main Code Implementation**: There are three versions of the code, each targeting different scenarios: normal charging speed, half charging speed, and double charging speed. Each file corresponds to a specific scenario. For example, in the normal speed case, adjust the parameters and Gurobi license information accordingly. Running the code will yield numerical results, including outcomes with different budget levels and initial charge distributions.
2. **Input Folder**: This folder contains all the necessary data for running the code under the Sonoma County wildfire case study. For other cases, you will need to create the corresponding files yourself.
3. **Output Folder**: This folder contains all the data generated from running the code. There are two subfolders: one for the output of initial charge level distributions and one for the numerical results. You can also generate these by running the code yourself.
4. **License Folder**: The "y" folder contains a valid Gurobi license. You may replace it with your own Gurobi license, but be sure to update the path in the code accordingly.
