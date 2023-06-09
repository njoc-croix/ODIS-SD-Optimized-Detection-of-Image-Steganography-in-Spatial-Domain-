Introduction

The primary focus of ODIS-SD is to enhance the precision of steganalysis in the detection of digital images containing sensitive information. The effectiveness of ODIS-SD is assessed using the BOSSBase version 1.01 dataset alongside two adaptive steganography algorithms (WOW and S-UNIWARD) with payload sizes of 0.2 and 0.4 bits per pixel (bpp). The outcomes reveal a significant enhancement in detection accuracy ranging from 2.1% to 3.6% in comparison to prior research endeavors.

Citing

If you find this work valuable for your research or if our comprehensive paper with all the results proves useful, we kindly request that you acknowledge our contribution by including a citation to our paper at: https://ieeexplore.ieee.org/document/10082736 

N. J. de La Croix and T. Ahmad, “Toward Hidden Data Detection via Local Features Optimization in Spatial Domain Images,” in 2023 Conference on Information Communications Technology and Society (ICTAS), IEEE, Mar. 2023, pp. 1–6. doi: 10.1109/ICTAS56421.2023.10082736.


To run this model, follow these steps: 

1.	Load all the eight files (X_train, X_test, X_valid, y_train, y_test, y_valid, SRM.npy, SIMPA_Jean_ICTAS.ipynb) in the same folder. 
2.	Create the necessary folders for the trained models and results as in indicated in the main file, and put the file called Best_trained_model.hdf5 in the created trained modeles folder. 
4.	To run the CNN, you need to have "TensorFlow, os, scikit-image, NumPy, OpenCV, Matplotlib, Time, and glob."


Notice

Before running the notebook in the main_file, please verify that the file paths are correct, and all libraries are installed.


Thank you for considering our code and giving suggestions on how to make it more user-friendly!
