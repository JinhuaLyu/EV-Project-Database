### Read Me

1. The "code" folder contains all the necessary code for our project.
   - First, initialize the car numbers at different charge levels at various nodes using "car_number_initialization_normal.ipynb," which generates three different cases for normal charge speed.
   - Second, implement the main code. There are three versions of the code, each targeting different scenarios: normal charging speed, half charging speed, and double charging speed. Each file corresponds to a specific scenario. For instance, in the normal speed case, adjust the parameters and Gurobi license information accordingly. After running the code, you will obtain numerical results, including outcomes with different budget levels and initial charge distributions.
2. The "input" folder contains all the necessary data for running the code under Sonoma County wildfire case study. If you want to other cases, you need to create the corresponding file on your own. 
3. The "output" folder contains all the data generated from running the code. You can also generate these by running the code yourself.
4. The "y" folder contains a valid Gurobi license. You may replace it with your own Gurobi license, but be sure to update the path in the code accordingly.