# renewal_processes
Data coming from simulated Discrete Renewal Process Mixtures.
The method of generation is described in the paper "Deinterleaving of Discrete Renewal Process Mixtures with Application to Electronic Support Measures".
One repository by number of symbols
file name: 'sc_+ scenario number + 'lettres ' + number of symbols + '_' + sequence length + type of data
  number after 'sc_' : scenario numerotation
  number after 'letters_ : number of symbols
  third number : sequence length
Two files for one scenario :
  'sequence' file contains the "observed data", composed of two lines :  thre first one with the symbol sequence, the second line contains their time of arrival.
  'target' file contains the ground truth, each line corresponds to the sub alphabet of one process.

  

