# ann-guide

import os 
import urllib 
import zipfile

//Download and unzip the dataset if not os.path.isfile('.zip'): urllib.request.urlretrieve("https://github.com/Gurupatil0003/Brain-Tumor-Data-set/archive/refs/heads/main.zip", "Brain Tumor Data Set.zip")

zip_filename = "Brain Tumor Dataset.zip" with zipfile.ZipFile("Cat Dog Data Set.zip","r") as zip_ref: zip_ref.extractall(".")
