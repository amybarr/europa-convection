# europa-convection
Data and codes for simulating convection on Europa, specifically lenticulae formation.  
CITCOM.tar includes the version of CITCOM used in the study as well as some sample input files.
For more information or technical assistance, contact amy@psi.edu

Some sample outputs are shown in the files called, e.g., "v2-periodic-data.tar"  

The outputs, "node_data" files are the raw results simulations of ice convection in a 2-dimensional Cartesian geometry in an 8x1 box. There are 513 nodes in the x direction and 65 nodes in the z direction.

The input files for each case are the ".par" files.

The columns in the node_data files are:
Node number
X
Z 
Y (always =0 because we're in 2d)
X velocity
Z velocity
Temperature
Pressure
Streamfunction
Viscosity
Strain rate (edot)
and Stress (strs)

The quantities are non-dimensionalized using values that appear in the Rayleigh number.  For example, "time" is measured in units of thermal diffusion time.  Distance is scaled with the thickness of the ice shell.

Simulations in the "v2" tar ball have a viscosity ratio between the surface and basal ice of 10^2.  All of the data up here so far is for basally heated convection.


