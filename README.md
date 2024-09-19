# DevOps-Project-Multi-Tier-Bank-Application-Pod-based-Azure

![image](https://github.com/user-attachments/assets/cd5b4cdc-9432-4b46-890b-3a3cf850f2f9)

Source Code is present in the Azure Repos as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/d7bcffdf-36e1-4138-abfd-1a036fa2376d)
![image](https://github.com/user-attachments/assets/b42fae0f-915c-4148-9843-9e97e1be39a0)

Service Connection is created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/01eac503-8b7f-4c5c-81c5-36088d4f4669)

Azure DevOps Pipelines for bankapp and mysql has been created using the azure-pipelines-bankapp.yaml and azure-pipelines-mysql.yaml as present with this Repository. 
![image](https://github.com/user-attachments/assets/0ea66f99-929a-44c6-b2ef-a2d51eb892bf)

The screenshots for SonarQube, Azure Artifacts Feed after running the pipelines mysql and bankapp is as shown below.
![image](https://github.com/user-attachments/assets/8eb87172-c693-4eca-bbb4-68f26d61fe46)
![image](https://github.com/user-attachments/assets/3ca1f177-af24-48d8-8514-3d8adfa4afdd)

Pod, Service and Deployment for BankApp has been created after successfully running the Azure DevOps Pipelines is shown below.
![image](https://github.com/user-attachments/assets/e2695c7d-27d8-4ba9-b571-fde4bd55cb15)

Entry into the MySQL8 database pods after registrering a new user is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/6325fb93-533c-446d-8993-14a8515cba2d)
![image](https://github.com/user-attachments/assets/44b5900f-65b1-4518-b646-1c1dd2e3e4cd)

Entry into Azure DNS Zone is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/6791c88b-3a88-489c-9383-482683af7189)

Finally access the bank application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/a5c143d4-3a8c-4340-aa12-57677434e500)
![image](https://github.com/user-attachments/assets/13008d2e-ffa2-4f6e-92a4-cb38c30952ce)

```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=qXXXXXXXXXXXXXXXXrCHXXXXXXXXXXXXXXXXV0zXXXXXXXXXXXX7 -n bankapp
```
<br><br/>
<br><br/>
```
OpenJDK Docker Image is depricated so in this project eclipse-temurin docker image has been used as a base image in the Dockerfile. 
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:-   https://github.com/kamalmohan217/Bank-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
