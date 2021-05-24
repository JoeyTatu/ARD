# [National College of Ireland](https://ncirl.ie)
# BSc. (Honours) in Computing
# Software Development
# 2020/2021
# Joey Tatú
# 15015556
# [joey.tatu@student.ncirl.ie](mailto:joey.tatu@student.ncirl.ie)

# Executive Summary
Automatic Retinopathy Detection Using Digital Image Processing via a Smart Device 
The purpose of this report is to provide an overview of the project, to explain the main functional and non-functional requirements and to discuss the overall look of the project. Beyond these, how the project is implemented is also considered, as well as explaining the process of testing and evaluation. 

The main focus of this project is to detect diabetic retinopathy by using an app on a smart device. Future versions of the app are expected to be able to be connected to a Raspberry Pi. This Raspberry Pi will be connected to a macro lens camera that will be able to take close-up photos of the inside of the eye. 
Other future features include connecting to a database (such as a doctor surgery or hospital records). This will allow the generated results from the app to be sent to the database. This database can be used in connection to the patient’s online records to keep all their data in one place. Future versions of the app will also be able to update the medical information from the app such as the patient’s medical information such as their weight, blood sugars, other illnesses and what medications the patient is taking. 

The results of scanning a patient’s eye will be able to determine if a patient has diabetic retinopathy (DR) by determining what DR stage the patient is at, with stage I having no DR, stage IV having severe DR and stage V expected to have DR in the future.Executive SummaryIf stage I is detected, no action would be required. With stages II – V, the app would automatically update the patient’s record. This is done by comparing the uploaded image of the eye with a TensorFlow Lite generated model. 

The conclusion to the project is that a preliminary test can be completed by a medical professional on a patient before and if further testing of the patient’s eyes is needed.

