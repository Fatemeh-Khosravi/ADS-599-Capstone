## Dataset Description

The selected dataset is the CT-ICH (Computed Tomography - Intracranial Hemorrhage) dataset. It consists of 2,500 head CT images in jpg format (650*650 pixel), specifically brain window. These images belong to 82 different patients, with approximately 30 image slices per patient.The dataset includes CSV files containing hemorrhage diagnosis. 

Origin: Kaggle https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images

* File Types: CSV, JPG
* File Size: 118.7 MB
* Modeling Problem: Classification
* Missing Values: No
* Duplicated Values: No
* Unbalanced Dataset: Yes 

## Feature Descriptions

* PatientNumber : Numerical indicators assigned to each patient starts from 49.
* SliceNumber :  Numerical indicators assigned to each image slice starts from 1. 
* Intraventricular : Assigned a value of 1 or 0 based on whether the patient has intraventricular hemorrhage.
* Intraparenchymal : Assigned a value of 1 or 0 based on whether the patient has Intraparenchymal hemorrhage.
* Subarachnoid : Assigned a value of 1 or 0 based on whether the patient has Subarachnoid hemorrhage.
* Epidural : Assigned a value of 1 or 0 based on whether the patient has Epidural hemorrhage.
* Subdural : Assigned a value of 1 or 0 based on whether the patient has Subdural hemorrhage.
* Fracture_Yes_No : Assigned a value of 1 or 0 to indicate the presence or absence of a fracture in the patient.

Target Feature:
* No_Hemorrhage : Assigned a value of 0 or 1 to indicate the presence or absence of a hemorrhage in the patient.

