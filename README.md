# LIBS Peak Find GUI
## Peak Finder App: A Graphical User Interface for Quick and Efficient Interactive Detection of Peaks in a LIBS Spectrum

By [Manoj Kumar Gundawar](http://www.acrhem.org/manoj.html) , Amal, and, [Rajendhar junjuri](https://scholar.google.co.in/citations?user=BRu_wuAAAAAJ&hl=en)

This Graphical User Interface is developed for the detection of peaks in a LIBS spectrum. This app is not only quick and effective but is also highly interactive and intuitive. A LIBS spectrum contains a large number of peaks representing the constituent atoms of the material under investigation. Given the varied nature of these peaks, finding all the peaks of interest is a tedious and often time-consuming task. This GUI can facilitate researchers worldwide who are engaged with LIBS data analysis by streamlining the process, ensuring ease and intuitiveness while also accurately detecting all the desired peaks. Particularly, an option to find the peaks in a sub-spectrm makes it a very powerful tool. The GUI additionally serves as a tool for exploring the spectrum with specialized functionalities of zoom-out and auto-stepper. These options open up a new avenue for LIBS researchers, which will augment their initial data comprehension. The information of the peaks found is saved interactively, which is crucial for various downstream analyses. 

## The article can be accessed here
DOI: Will be updated soon

## Citation
Will be updated soon

## For more related articles
https://scholar.google.co.in/citations?user=lCVwC0EAAAAJ&hl=en

## Installation details of the App
LIBS_peak_finder Executable

1. Prerequisites for Deployment 

Verify that version 9.12 (R2022a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2022a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-LIBS_peak_finder.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

## Test data
The App is tested on the following samples. All the input files are in .txt format
1.Plastics
2.Silicon
3.Isomer
4.Tooth
5.Nicke
6.Soil



details of the 300 synthetic test spectra

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


## Getting Started and Requirements 
You can use Python (TensorFlow 2.7.0) to test the pre-trained network. We have tested it in Spyder.
