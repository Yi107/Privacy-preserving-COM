

# Privacy-preserving Cooperative Online Matching in Spatial Crowdsourcing

This repository stores the executable files of two algorithms proposed in the paper and the data set used in experiment.



## The usage of the algorithms

Executable files are provided to get the results of the algorithm.



For D-PCOM algorithm, you can run this command in terminal: "DPCOM *workerdatafile* *requestdatafile* $\epsilon_1$ $\epsilon_2$ *outputfilename*", where DPCOM is the executable file of D-PCOM algorithm, *workerdatafile* is the file name of worker data, *requestdatafile* is the file name of request data, $\epsilon_1$ is the privacy level of the location of cooperative request, $\epsilon_2$ is the privacy level of the pricing mechanism, and *outputfilename* is the name of the output file.



For S-DCOM algorithm, you can run this command in terminal: "SPCOM *workerdatafile* *requestdatafile* $\epsilon_1$ $\epsilon_2$ *outputfilename*", where SPCOM is the executable file of S-PCOM algorithm, and the parameters remains the same meaning.



After running the .exe file, you can obtain the results of algorithm in file **outputfilename**. 



## Description of the dataset

For the dataset of worker, it contains 9 parts. Id, Platform id, Radius, Apperance time, Latitude of apperance location, Longtitude of apperance location, Historical request value, Historical unit price, The distribution of historical unit price.



For the dataset of request, it contains 10 parts. Id, Platform id, Apperance time, Finishing time, Latitude of apperance location, Longtitude of apperance location, Latitude of ending location, Longtitude of ending location, Travel distance, Payment.



The real dataset used in the experiments is in folder **Real Data** and the synthetic data is in folder **Syn data**.

To run the experiments on real data, please use the dataset contains the union of three platforms. (i.e. CN01_W and CN01_R)



