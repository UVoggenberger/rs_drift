# rs_drift

https://github.com/UVoggenberger/rs_drift/tree/main

This is a simple package to calculate the drift of radiosondes.

The uncertainty of upper air observations depends not only on the measurements themselves but also on the availability and quality of metadata.
It is well known that weather balloons drift with the wind during ascent and thus can travel large distances, in some cases more than 400 km. 
For a long time, for most balloon ascents, the information regarding the position was not recorded or was not transferred to the data distribution networks.

To reconstruct the trajectories or the drift of those radiosondes, this package will use a methode based on wind information.
Input data must contain temperate, pressure and also wind components in the form of eastward (u) and northward wind (v).

Example Notebook: https://github.com/UVoggenberger/rs_drift/blob/main/rs_drift_example.ipynb
