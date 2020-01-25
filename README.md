# Neural Network for Sequence Data

Ths is a simple example of gene sequence analysis using neural networks. It is adapted from https://github.com/const-ae/Neural_Network_DNA_Demo to run on the MIT Satori PowerAI Cluster.

We will take a collection of sequences plus information if they are 
bound by a transcription factor as input data and after training
a convolutional neural network we will be able to make predictions 
for new sequences. In addition we will extract what the network learned
and make a plot of the motif.

The example are chosen such that it is not necessary to have a GPU and
should learn just fine on a CPU.


# To deploy on Satori do the following:

Get access to Satori following instructions in the Satori Documentation
Point your browse to the Satori Open On-Demand (OOD) portal
On the top menu bar got to Clusters -> Satori Shell Access
Install keras using "conda install keras" 
In the shell get the test repo by typing git clone https://github.com/choudary21/Neural_Network_DNA_Demo
Once the git clone is done, go back to the OOD Dashboad window (labeld My Interactive Sessions) and go to menu option Interactive Apps -> Jupyter Notebook
Click the Launch button to fire off a Jupyterlab session
Click the Connect to Jupyter button when it appears in a few moments
When Jupyter comes up for the first time, you may be prompted to select a kernel, If so, choose the default Python 3 PowerAI
Use the left navigation pane to find the git repo directory (Neural_Network_DNA_Demo) you downloaded in step 4. . click into it and dopuble click on the Jupyter notebook nn_for_sequence_data.jpynb
Run the Jupyter frames one by one using the 'play' arrow button to test.. or go to the menu option Run -> Run all cells intermediate results will appear at the bottom as the program runs
Enjoy !!!




