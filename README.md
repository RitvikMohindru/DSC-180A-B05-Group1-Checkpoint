# DSC-180A-B05-Group1-Checkpoint

Neccessary Dependencies:
- netcdf4 xarray[io] cartopy nc-time-axis siphon scikit-learn warnings os copy h5py pandas

Replicability Steps:
NOTE: to run output_data_processing.ipynb, you will need access to NorESM2 raw outputs for every listed experiment, which is too large to put onto github. Also note that the work so far is all written in jupyter notebooks, there is no commands neccessary for results replication. 
1. Ensure you have NorESM2 raw output data
2. Ensure you have a folder to store the processed output data, and its name matches the OUT value within output_data_processing.ipynb.
3. Run all cells in output_data_processing.ipynb, this will populate the OUT folder with processed NorESM2 output data, separated into 3 folders, one for each output variable.
4. Run all cells in baseline_models.ipynb, doing so will replicate the results that we've found. 