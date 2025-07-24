This repository contains the data employed for the article:

"Nonequilibrium thermometry via an ensemble of initially correlated qubits"

Enrico Trombetti*, Marco Pezzutto, Marco Malitesta, Stefano Gherardini

https://arxiv.org/abs/2507.03471

*enrico.trombetti@ino.cnr.it

## ABSTRACT
"We investigate a nonequilibrium quantum thermometry protocol in which an ensemble of qubits,
acting as temperature probes, is weakly coupled to a macroscopic thermal bath. The temperature of the bath, the parameter of interest, is encoded in the dissipator of a Markovian thermalization process. For some relevant initial states, we observe a peak in the Quantum Fisher Information (QFI) during the transient of the thermalization, indicating enhanced sensitivity in early-time dynamics. This effect becomes more pronounced at higher bath temperatures and is further enhanced when the qubits’ initial state has a larger ground-state population. Our analysis shows that both local coherence in the probes’ initial state and initial correlations among the probes contribute to the amplification of the peak in the QFI, thus improving the precision of the temperature estimation. The influence of quantum correlations emerges as a central feature of this work. Although the dynamics does not permit superlinear scaling of the QFI with the number of probes, we identify the most effective initial states for designing high-precision quantum sensors within this setting. We also provide concrete guidelines for experimental implementations."

## REPOSITORY CONTENT
All the data used for the plots of the above mentioned article are saved in .dat files inside the "data" folder. The Jupiter Notebook "plots_nonequilibrium_thermometry_via_an_ensemble_of_initially_correlated_qubits.ipynb" contains some short Python scripts that reproduce almost all figures from the paper, using the values contained in the "data" folder.

## DATA STRUCTURE
The numbering follows that in the article.
### figure_02a.dat, figure_02b.dat, figure_02c.dat
dimensions: (5,2,1600)
5 temperatures
2 arrays of values: time and QFI
1600 values for each array
### figure_03.dat
dimensions: (6,2,1600)
6 values of mu
2 arrays of values: time and QFI
1600 values for each array
### figure_04.dat
dimensions: (4,80,2)
4 temperatures
80 pair of values
2 values per pair (mu, max(F_Q)-F(th))
### figure_05.dat
dimensions: (5,40,2)
5 values of eta
40 pair of values
2 values per pair (beta, v_mu)
### figure_06.dat
dimensions: (6,60,2)
6 values of a
60 pair of values
2 values per pair (beta, v_r)
### figure_07a.dat, figure_07b.dat, figure_07c.dat
dimensions: (11,2,1600)
11 values of eta
2 arrays of values: time and QFI
1600 values for each array
### figure_08.dat
dimensions: (6,60,2)
6 values of mu
60 pair of values
2 values per pair (beta, v_eta)
### figure_09abc.dat
dimensions: (21,6,1600)
21 values of chi
6 arrays of values: time, QFI, negativity, (empty) , concurrence, mutual information
1600 values for each array
### figure_09d.dat
dimensions: (21, 2, 3000)
21 values of chi
6 arrays of values: time, purity
3000 values for each array
### figure_10.dat
dimensions: (6, 1600, 2)
6 values of chi
1600 pair of values 
2 values per pair (time, QFI difference)
### figure_11abc.dat
dimensions: (21,6,1600)
21 values of alpha
6 arrays of values: time, QFI, negativity, (empty) , concurrence, mutual information
1600 values for each array
### figure_11d.dat
dimensions: (21, 2, 3000)
21 values of alpha
6 arrays of values: time, purity
3000 values for each array
### figure_12.dat
dimensions:(6,5,2)
6 initial states
5 points for each state
2 values per pair (N, QFI)

## ADDITIONAL INFORMATION
Additional information is available upoun request by email
