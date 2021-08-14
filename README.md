# 3DCNN-for-Hyperspectral-Image-Classification

Project contains the following functions
1. loadDataSet()
2. applyScaling()
3. applyPCA()
4. padWithZeros()
5. createPatches()
6. getIndices()
7. splitTrainTestSet()

For Plotting and metrics claculation it uses the following functions
1. plot_signature()
2. plotExplainedVarienceRatio()
3. plotConfusion()
4. AA_andEachClassAccuracy()
5. reports()

Additionally it contains the DataGenerator Class this is used to handle memory and multiprocessing.

To run this upload the notebook to Google Colab it has most of the modules preinstalled.

If you want to run this locally install the following modules
1. numpy
2. scipy
3. matplotlib
4. spectral
5. sklearn
6. tensorflow

Store the dataset in the same directory as the notebook. Currently the loadDataSet function is defined for the datasets Indian Pines, Pavia University, Salinas, Kennedy Space Center and Botswana. If you want to try other datasets add the implementation into the loadDataSet function.
