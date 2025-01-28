# Burn Scar Geospatial Foundation Model

## Description
This projects purpose is to train and study a model which segments satellite image data of an area of land which has been damaged by a wildfire, 
into burned and unburned areas, without having to be specifically told which areas in the relevant image are burned. This is using a geospatial foundation model, built on a prithvi backbone,
developed by IBM. 

## Installation
This project was done on Jupyter Notebooks in Google Colab, and as such, simply downloading the .ipynb file and uploading to Google colab will allow for full use of the code shown. Further 
information and the source code can be found on the IBM hugging face website and Github page, from which the example notebook for this code was taken:

https://github.com/IBM/terratorch/blob/main/examples/notebooks/Tutorial.ipynb

Config file: https://github.com/IBM/terratorch/blob/main/examples/confs/burn_scars.yaml

https://huggingface.co/ibm-nasa-geospatial

All of this is open source.

### Use
As stated, by downloading the .ipynb file and uploading it to Colab, it can be used as is with no need for anything else (except a GPU). 
Some points to note about using this specific file:

A GPU IS NEEDED FOR THE MACHINE LEARNING MODEL TO FUNCTION.

Colab allows for free usage of the Tau 4 GPU, which can be done by clicking 'Change runtime type' under the runtime tab. 

For installation of terratorch, a warning message will pop up saying the session has to be restarted. Click restart, and run only the cells below the terratorch download.

Thats all thats needed. As can be seen, I have a lot of print statements to keep track of things, as the directories are tricky. 

Thanks to Paolo Fraccaro and his team in the UK for all their help with my small part in this amazing project!



