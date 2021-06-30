# MRGENESIS-load

This repository contains example code for reading the [MRGENESIS](https://ui.adsabs.harvard.edu/abs/2009ApJ...696.1142M/abstract) hydro files. The following files are included:

- [load_and_display.ipynb](https://github.com/petarmimica/MRGENESIS-load/blob/main/load_and_display.ipynb): the Jupyter notebook containing the code
- k_1_n18_60-00277.h5: a sample hydro snapshot
- 60.mp4: a movie showing the full hydro evolution
- [load_and_display_1D.ipynb](https://github.com/petarmimica/MRGENESIS-load/blob/main/load_and_display_1D.ipynb): the Jupyter notebook containing the code to read 1D files
- 60_10_le-00046.h5: a sample 1D hydro snapshot
- 1D_model: a folder containing sample 1D model (see below)


To proceed, please open the [notebook](https://github.com/petarmimica/MRGENESIS-load/blob/main/load_and_display.ipynb).

## 1D model

There are actually two 1D simulations: a relativistic (Lorentz factor 10) and mildly relativistic (Lorentz factor 2) runs. In order to correctly compute the light curves it has to be assumed that the relativistic component subtends an angle from 0 to 0.1 rad and that the mildly relativistic one goes from 0.1 to 0.5 rad.

The files are:
- [60_2_le-01996.h5](https://github.com/petarmimica/MRGENESIS-load/blob/main/1D_model/60_2_le-01996.h5): the mildly relativistic component at ~1500 days (lab frame)
- [60_2_le-02200.h5](https://github.com/petarmimica/MRGENESIS-load/blob/main/1D_model/60_2_le-02200.h5): the mildly relativistic component at ~2300 days (lab frame)
- [60_10_le-01996.h5](https://github.com/petarmimica/MRGENESIS-load/blob/main/1D_model/60_10_le-01996.h5): the relativistic component at ~1500 days (lab frame)
- [60_10_le-02200.h5](https://github.com/petarmimica/MRGENESIS-load/blob/main/1D_model/60_10_le-02200.h5): the relativistic component at ~2300 days (lab frame)
