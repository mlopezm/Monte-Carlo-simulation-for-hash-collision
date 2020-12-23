# Monte-Carlo-simulation-for-hash-collision
Monte carlo simulation for NAEs hash collision

This simulation is part of the work done in the following work: “Network intrusion detection with a novel hierarchy of distances between embeddings of hash IP addresses”, Manuel Lopez-Martin, Belen Carro, Juan Ignacio Arribas, Antonio Sanchez-Esguevillas.

The simulation scope extends to the following scenarios:
1.	Simulate the simultaneous collision using the IP, Port and IP&Port NAEs with the total number of NAEs present in the CICIDS2017 dataset: 8330, 62434 and 218406 different values for the (source and destination) IP, Port and IP&Port NAEs, respectively. The simulation is done with a maximum hash value of 3000.
2.	Simulate the simultaneous collision using only the IP and Port NAEs with the total number of NAEs present in the CICIDS2017 dataset: 8330, 62434 different values for the (source and destination) IP, Port and IP&Port NAEs, respectively. The simulation is done with a maximum hash value of 3000.
3.	Simulate the simultaneous collision using the IP, Port and IP&Port NAEs with a reduced number of NAEs and maximum hash value. The number of NAEs and maximum hash value has been scaled down with a factor of 100.

The code for the first scenario is in the file: Calc probability collision.R

The code for the second scenario is in the file: Calc probability collision ip and port only.R

The code for the third scenario is in the file: Calc probability collision scaled-down version.R

The simulation has been done in R 

Along with the R code files, there is an attached html file to make the files easier to read.

The code is prepared to be executed in the cloud using Google Colaboratory https://colab.research.google.com/notebooks/intro.ipynb

We have also included the simulation outputs for the first scenario
