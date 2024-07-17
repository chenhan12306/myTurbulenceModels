This README outlines the setup and execution of an OpenFOAM simulation 
for the T3C1_ercoftac test case. Experimental data for this case is available 
on the website: [Ercoftac experiments](http://cfd.mace.manchester.ac.uk/ercoftac/doku.php?id=cases:case020).

# Turbulence Model:

The turbulence model used in this simulation is **gammaSST**.

# Instructions:

## Clean the directory:
- Before running the simulation, it is necessary to clean the directory by executing the following command: **./Allclean**

## Run the simulation:
- To run the simulation, execute the following command: **./Allrun**

# Analyze results:
Once the simulation is complete, you can analyze the results by plotting the friction coefficient (Cf) versus the Reynolds number (Rex). 
This can be done using data visualization tools such as ParaFoam or Tecplot.

**Notes:**

- Make sure you have OpenFOAM installed and your environment is set up correctly.
- The mesh and configuration files for this simulation are included in the current directory.
- You can modify the simulation parameters by editing the corresponding configuration files.

**References:**
[reference](http://cfd.mace.manchester.ac.uk/)
