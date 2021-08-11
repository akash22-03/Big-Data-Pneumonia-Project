# Big-Data-Pneumonia-Project
<h2><strong>Big Data Management System (BDMS)</strong></h2>
<h3>Problem statement</h3>
Pneumonia is in the list of top 10 causes for death in the US. It accounts for 15% of all death in children under the age of 5 internationally. Accurately diagnosing Pneumonia is an elaborate process. It requires review of Chest Radiograph by trained specialists and other detailed examination. Due to the high volume of Chest X-Ray review the specialists are burdened with, screening the radiographs for opacity which indicated pneumonia using AI to prioritize and expedite review is seen a possible solution.

<h3>The Dataset - BIG DATA</h3>
The dataset contains images with details in DICOM® format. DICOM® (Digital Imaging and Communications in Medicine) is the international standard to transmit, store, retrieve, print, process, and display medical imaging information. DICOM images are special images with metadata. Each image has information about itself.

The actual data set that has 26684 training and 3000 test X-ray images. The images are annotated with bounding boxes to highlight the region in the X-ray that is indicative of possible Pneumonia. For the purpose of this training, we have reduced it to 100 images and their respective data in the file Patient_images.zip. Unzip this file into a directory named "stage_2_train_images". *To make it more challenging, find the package python uses to unzip and you can unzip the file in your code*

<h3>The normal structured data</h3>
All the patient outcomes and the infected area are stored in the CSV File Patient_details.csv. This also contains 100 records which pertain to each of the patients whose image details we have in the zip file. 
