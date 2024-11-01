# Quality-of-Transmission-QoT-estimationin-opticalnetworks


What happens with the margin if some features are not known precisely?

E.g., span lengths are decided at the network design phase but the actual values in the field may be slightly different
Evaluate the impact of uncertain fiber span length
b)
Consider NN algorithm only and redo training and performance evaluation using a new dataset with uncertain features, where error in span length is introduced with std dev = to 5%, 10%, 15% of the maximum span length across all lightpaths. Specifically, after reading the dataset (task 1b), for each error std dev, the steps are:

1- generate features matrix 

2- splitand scale the dataset and train a new NN 

3- predict and evaluate performance 

This repository contains in-class activities for the "Network Measurement and Data Analysis" course taught by [Prof. Redondi](https://scholar.google.com/citations?user=8ka5NmUAAAAJ&hl=en) and [Prof. Musumeci](https://scholar.google.it/citations?user=RsM0KB0AAAAJ&hl=it) at Politecnico di Milano.
