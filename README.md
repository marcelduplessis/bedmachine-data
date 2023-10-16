# bedmachine-data
Loading and plotting BedMachine Antarctica data

Taking the BedMachine data and using https://github.com/nsidc/nsidc0756-scripts/ example to read in the data, covert polar stereographic (x, y) coodinates to geodetic (latitude, longitude) coordinates and then interpolates value from the BedMachineAntarctica netcdf file onto requested (x, y) polar stereographic coordinates.

To see what I do, follow the code in `read-bedmachine.ipynb`, just change the path of the data and make sure the `.py` files are in the folder you're working in.
