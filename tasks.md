# QRMA-1

## Data

- Paderborn Bearing Dataset
- EEG
- Unified System

## Data Processing Algorithm

1. Calculate a median frequency for each signal
2. Calculate a mean frequency of the dataset ($f_m$)
3. Calculate a mean period ($\tau_m = 1/f_m$)
4. Select the number of periods (ex. $n=10000$)
5. Calculate the signal length ($\tau_m\cdot n$)
6. EMD
7. RMA
8. QRMA (distance-RMA or graph-RMA)

## To Do

- [ ] calculate $\tau_m$ for bearings
- [ ] revise and recompute the experiments for bearings. to watch for:
  - [ ] use $\tau_m$
  - [ ] try again with all of the bearings
  - [ ] try only bearings with the real damage


## Experiments already conducted


## Results

