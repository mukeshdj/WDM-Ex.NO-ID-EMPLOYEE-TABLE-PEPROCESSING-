# WDM-Ex.NO-1D-EMPLOYEE-TABLE-PEPROCESSING
## Name: MUKESH S
## Reg.no: 2305002016
## Aim:
To apply Pre-Processing techniques to the training data set of Employee Table
## Description:
Real world databases are highly influenced to noise, missing and inconsistency due to their queue size so the data can be pre-processed to improve the quality of data and missing results and it also improves the efficiency.
There are 3 pre-processing techniques they are:
1)	Add
2)	Remove
3)	Normalization
## Procedure:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Employee Table.

```@relation employee 
@attribute name {x,y,z,a,b} 
@attribute id numeric
@attribute salary {low,medium,high} 
@attribute exp numeric
@attribute gender {male,female} 
@attribute phone numeric

@data 
x,101,low,2,male,250311 
y,102,high,3,female,251665 
z,103,medium,1,male,240238 
a,104,low,5,female,200200 
b,105,high,2,male,240240
```
3)	After that the file is saved with .arff file format.
4)	Minimize the arff file and then open Start  Programs  weka-3-4.
5)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)	In that dialog box there are four modes, click on explorer.
7)	Explorer shows many options. In that click on ‘open file’ and select the arff file
8)	Click on edit button which shows employee table on weka.
 
## Training Data Set - Employee Table
<img width="730" height="791" alt="image" src="https://github.com/user-attachments/assets/918699eb-cdc2-4471-a50f-7fad5b0e330b" />

## Add Pre-Processing Technique:
Procedure:
1)	Start  Programs  Weka-3-4  Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Employee.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Add.
9)	A new window is opened.
10)	In that we enter attribute index, type, data format, nominal label values for Address.
11)	Click on OK.
12)	Press the Apply button, then a new attribute is added to the Employee Table.
13)	Save the file.
14)	Click on the Edit button, it shows a new Employee Table on Weka.
 
## Employee Table after adding new attribute ADDRESS:
<img width="770" height="377" alt="image" src="https://github.com/user-attachments/assets/89d8d87e-720a-4b2f-a5c3-42d8a92acc0f" />

## Remove Pre-Processing Technique:
Procedure:
1)	Start  Programs  Weka-3-4  Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Employee.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Remove.
9)	Select the attributes salary, gender to Remove.
10)	Click Remove button and then Save.
11)	Click on the Edit button, it shows a new Employee Table on Weka.
 
## Employee Table after removing attributes SALARY, GENDER:
<img width="1067" height="307" alt="image" src="https://github.com/user-attachments/assets/e794b10f-16f1-48b7-bb29-1ca2fb0b3210" />

## Normalize -Pre-Processing Technique:
Procedure:
1)	Start  Programs  Weka-3-4  Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Employee.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Normalize.
9)	Select the attributes id, experience, phone to Normalize.
10)	Click on Apply button and then Save.
11)	Click on the Edit button, it shows a new Employee Table with normalized values on Weka.
 
## Employee Table after Normalizing ID, EXP, PHONE:
<img width="668" height="361" alt="image" src="https://github.com/user-attachments/assets/14472ba1-9caf-499f-8851-d0b195014da0" />

## Result:

Thus, this program has been successfully executed.
