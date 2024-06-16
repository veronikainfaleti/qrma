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
6. Normalize the signal
6. EMD
7. RMA
8. QRMA (distance-RMA or graph-RMA)

## To Do

- [ ] [eeg] add random electrodes list and iterate through it (see **emd_bearings.m** file)
- [ ] [bearings] add random recording list and iterate through it (see **emd_bearings.m** file)
- [ ] revise and recompute the experiments for bearings. to watch for:
  - [ ] use $\tau_m$
  - [ ] try again with all of the bearings
  - [ ] try only bearings with the real damage

- [ ] calculate **EMD** for eeg


## Done

- [x] visualise time series of eeg with peaks (all right)
- [x] signals energy (std)
- [x] $f_m=0.6834$, $\tau_m=1.4634$ for eeg
- [x] $f_m=8849.4=8850$, $\tau_m=1.13e^-4$ for bearings
- [x] 2500 - time points for bearings
2500*1.463/0.113 = 32377
1.46/0.113=12.95
- [x] try to migrate EMD to python
- [x] to vary 'sd_thresh' in imfs - don't see a change, let it be equal to 0.1

## Experiments already conducted


## Results

