# Mean return time phase of an integrate-and-fire neuron with spike-triggered adaptation
Scripts for calculating a mean return time phase for an integrate and fire neuron with spike triggered adaptation.
Scripts relating to my master thesis.

# Numerical Approach

Main functionality for calculating isochrones can be found in https://github.com/sominsomin/mrt_phase_of_an_if_neuron/blob/master/mrt_phase_numeric/src/Isochrone/Isochrone.py.

Process:
- Create a data source: 
  - continous Timeseries : https://github.com/sominsomin/mrt_phase_of_an_if_neuron/blob/master/mrt_phase_numeric/src/DataTypes/TimeSeries/get_timeseries.py
  - Timeseries grid: https://github.com/sominsomin/mrt_phase_of_an_if_neuron/blob/master/mrt_phase_numeric/src/DataTypes/TimeSeriesGrid/get_timeseries_grid.py
  
- Edit config based on the data source:
  - https://github.com/sominsomin/mrt_phase_of_an_if_neuron/blob/master/mrt_phase_numeric/isochrones/get_isochrones/timeseries_config.py
  - https://github.com/sominsomin/mrt_phase_of_an_if_neuron/blob/master/mrt_phase_numeric/isochrones/get_isochrones/timeseries_grid_config.py
