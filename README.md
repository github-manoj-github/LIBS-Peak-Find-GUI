# LIBS-Peak-Find-GUI
## Peak Finder App: A Graphical User Interface for Quick and Efficient Interactive Detection of Peaks in a LIBS Spectrum

By [Manoj Kumar Gundawar](http://www.acrhem.org/manoj.html) , Amal, and, [Rajendhar junjuri](https://scholar.google.co.in/citations?user=BRu_wuAAAAAJ&hl=en)

This Graphical User Interface is developed for the detection of peaks in a LIBS spectrum. This app is not only quick and effective but is also highly interactive and intuitive. A LIBS spectrum contains a large number of peaks representing the constituent atoms of the material under investigation. Given the varied nature of these peaks, finding all the peaks of interest is a tedious and often time-consuming task. This GUI can facilitate researchers worldwide who are engaged with LIBS data analysis by streamlining the process, ensuring ease and intuitiveness while also accurately detecting all the desired peaks. Particularly, an option to find the peaks in a sub-spectrm makes it a very powerful tool. The GUI additionally serves as a tool for exploring the spectrum with specialized functionalities of zoom-out and auto-stepper. These options open up a new avenue for LIBS researchers, which will augment their initial data comprehension. The information of the peaks found is saved interactively, which is crucial for various downstream analyses. 

## The article can be accessed here
DOI: Will be updated soon

## Citation
Will be updated soon

## For more related articles
https://scholar.google.co.in/citations?user=lCVwC0EAAAAJ&hl=en

## About Synthetic test data and code
The details of the 300 synthetic test spectra

"y_test_300_merge_spectra3.npy"---> referes to the true Raman signal and data can be found here https://github.com/Junjuri/LUT/blob/main/y_test_300_merge_spectra3.npy

"x_test_300_merge_spectra3.npy"---> referes to the input CARS data and data can be found here https://github.com/Junjuri/LUT/blob/main/x_test_300_merge_spectra3.npy

Testing can be done by using the following program.
'RSS_Advances_CNN_prediction_on_test_data.py'. It can be found here https://github.com/Junjuri/LUT/blob/main/RSS_Advances_CNN_prediction_on_test_data.py

## About the experimental CARS test data
The experimental CARS test data set used in this investigation can only be provided upon request and can contact [Erik M. Vartiainen](https://research.lut.fi/converis/portal/detail/Person/56843?auxfun=&lang=en_GB) 

## About the training codes

1. CNN model trainin can be done by using this program 'RSS_Advances_CNN_to_train_with_different_NRBs.py' Please see here     https://github.com/Junjuri/LUT/blob/main/RSS_Advances_CNN_to_train_with_different_NRBs.py

2. Bi-LSTM model training can be done by using this program 'bi-LSTM_train.py'. 

3. LSTM model training can be done by using this program 'LSTM_train.py'. 

4. Vector model training can be done by using this program


## About the trained model weights

"CNN_model_weights can be found here https://github.com/Junjuri/LUT/blob/main/Polynomial_NRB_model_weights.h5 with a name 'Polynomial_NRB_model_weights.h5' 

"LSTM_model_weights.h5" --->referes weights of the model trained with LSTM.

"VECTOR_model_weights.h5" --->referes weights of the model trained with VECTOR can be accseed via request at ali.saghi.2015@gmail.com or rajendhar.j2008@gmail.com

"Bi_LSTM_model_weights.h5" --->referes weights of the model trained with Bi-LSTM

## Getting Started and Requirements 
You can use Python (TensorFlow 2.7.0) to test the pre-trained network. We have tested it in Spyder.
