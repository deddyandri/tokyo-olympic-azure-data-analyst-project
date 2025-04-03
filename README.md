# Tokyo Olympic Azure data analyst project

![image](https://github.com/user-attachments/assets/a48da2bf-b7a7-45ee-8e23-b0b12652ae9b)

## About datasets

2021 Olympics in Tokyo datasets, we get from kaggle

[datasets link](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

### Details
This contains the details of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021(2020) Tokyo Olympics.

This dataset contains the details of the Athletes, Coaches, Teams participating as well as the Entries by gender. It contains their names, 

countries represented, discipline, gender of competitors, name of the coaches.

athletes file consists of

![image](https://github.com/user-attachments/assets/a647a586-07e7-4e8f-a5dc-7c41b43b3213)

Coaches file consists of

![image](https://github.com/user-attachments/assets/fd411cea-94f8-4449-9b50-32684c811960)

EntrieGender file consist of 

![image](https://github.com/user-attachments/assets/7dba6aa6-992a-4eb2-a534-2308497fd6de)

Medals file consist of 

![image](https://github.com/user-attachments/assets/5430d58e-f74e-499d-a7ef-f5f646a096ed)

Teams file consist of 

![image](https://github.com/user-attachments/assets/8805559b-0abf-4d7e-9352-81ad0c3292c3)

## Steps

click on Storage Account on Azure platform

![image](https://github.com/user-attachments/assets/0ad07ea3-a636-4518-a5bb-fb12ff529bbc)

Azure storage account contains all of your Azure Storage data objects: blobs, files, queues, and tables. The storage account provides 

a unique namespace for your Azure Storage data that's accessible from anywhere in the world over HTTP or HTTPS. 

Data in your storage account is durable and highly available, secure, and massively scalable.

---

on Storage Accounts, select Create storage account

![image](https://github.com/user-attachments/assets/c66b9674-8a47-490a-8c99-1e674daa977d)

on Create a storage account, Create New Resource Group, by clicking "Create New

![image](https://github.com/user-attachments/assets/3a63fd15-371e-4f78-9a88-88ec1d094601)

we name it with tokyo-olympic, then OK

![image](https://github.com/user-attachments/assets/5c7aef72-c863-47f9-903f-81f09ae2404e)

type on Storage account name with with a name that has not been taken by someone else 

i type "inilatihanazure"

and Region, is the place where you live i prefer (Asia Pacific) Southeast Asia

![image](https://github.com/user-attachments/assets/7907d750-d559-4272-bb02-7a0fefe5a2d2)

for Performace, select Standard, and Redundancy, select Geo-redundant storage (GRS)

and make sure we check Make read access to data avalilable in the event of regional unavalability

![image](https://github.com/user-attachments/assets/e0907264-59b3-4e69-8cb1-6c0ba18dbe92)

click on Next

on security

check all 

![image](https://github.com/user-attachments/assets/0dfa025d-e4bc-4582-8fdf-2d937cad4e62)

on Access protocol, just ignore the boxes

![image](https://github.com/user-attachments/assets/b1b800a1-e832-4405-aaf2-290c50d54a56)

click next

on Network connectivity, select Enable Public access from all network

![image](https://github.com/user-attachments/assets/b9114b9f-66b8-47b6-b543-a9653affd7c0)

clck next

on Recovery, just ignore it, then Next

on encryption , just click Next

![image](https://github.com/user-attachments/assets/c66dafee-4255-45f9-8c10-440d2cec6649)

finally the result after review is 

![image](https://github.com/user-attachments/assets/c4980a4c-bfeb-42df-aafd-388ce5f03cb8)

click Create

after a vew minute process, we got an overview

![image](https://github.com/user-attachments/assets/aae9ecee-d047-437b-a29f-415470210705)

click on Go to resource

then we got overall Overview

![image](https://github.com/user-attachments/assets/c0875f7a-7f7f-4698-ac61-1ebd010920e4)


