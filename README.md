# Ex--6-AWS-Account-setup-and-S3-creation-

NAME: Keerthana 

REG NO: 212224220046

### Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

### Objectives
Create a Bucket in Amazon S3.
Add Objects (files and folders) to the bucket.
Access, move, download, and delete the objects.
Delete the Bucket.
### Illustration
Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

(<img width="887" height="468" alt="image" src="https://github.com/user-attachments/assets/1cbfec4b-d3c9-48c0-9bac-4cd551a7cfde" />
)

Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

<img width="887" height="425" alt="image" src="https://github.com/user-attachments/assets/b76161b6-eeba-4724-851e-b9789189ae52" />

<img width="887" height="467" alt="image" src="https://github.com/user-attachments/assets/bd0da290-f69e-4f52-9618-7bab1a32ede5" />

<img width="885" height="467" alt="image" src="https://github.com/user-attachments/assets/9ca7f633-af36-4b56-8ef8-6edb7d4f7253" />

<img width="1035" height="543" alt="image" src="https://github.com/user-attachments/assets/f0efbcf1-6bb0-4db9-bd2f-fb3753b53de3" />

<img width="992" height="518" alt="image" src="https://github.com/user-attachments/assets/6a3e4ebf-bbca-4422-b3b6-315eaa9c2577" />






For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

<img width="1032" height="522" alt="image" src="https://github.com/user-attachments/assets/f73daf7c-8ca5-45a3-a571-421b689c5813" />

<img width="465" height="402" alt="image" src="https://github.com/user-attachments/assets/9375b739-1fa4-47bf-b148-5392a0b72660" />



You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

<img width="1031" height="451" alt="image" src="https://github.com/user-attachments/assets/1234eab1-1955-46d4-8690-89508cd1f3e4" />


<img width="1036" height="486" alt="image" src="https://github.com/user-attachments/assets/ac0248e3-1a85-4fa4-89f3-49bb6e57e66f" />


Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

<img width="883" height="351" alt="image" src="https://github.com/user-attachments/assets/7a686830-8d0f-4ad2-aec4-04248d5aea3c" />


Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

<img width="350" height="357" alt="image" src="https://github.com/user-attachments/assets/1109f160-7d4d-458b-bcf7-ac6085fc901a" />

<img width="1041" height="435" alt="image" src="https://github.com/user-attachments/assets/7500b10a-b6cb-4184-9b26-b0122128b400" />



Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
