# Brain-Tumor-Classfication

Hello and welcome to our Brain Tumor detection system.
When downloading the three files, make sure that each of these files have the right paths for the code to work.
(Below are examples of where my file paths were for the marking of this Project)

1) GUI Capstone.ipynb 
  First, once you select MRI Scans. It will be saved here:
File Path: C:/Users/USER/Desktop/images taken

  Second, When clicking on the "Diagnoise" button it runs the file "Capstone Predictions.ipynb"
File Path: r"C:\Users\USER\Capstone Predictions.ipynb"

  Third, the results will be saved as an html file
File Path: r"C:\Users\USER\Desktop\Test Run\diagnosis_output.html

2) Capstone Predictions.ipynb
Make sure the file path you set for the images are the same file as the first step in "GUI Capstone.ipynb"
File Path: C:/Users/USER/Desktop/images taken

Make sure the model is also imported right by using Keras 
model = keras.models.load_model('mri_test.model')

3) Brain tumor classifcation.ipynb:

Make sure the dataset file path are correct. As shown in the "Brain Tumor Classifcation" image
