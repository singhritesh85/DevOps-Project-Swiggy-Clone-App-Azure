# DevOps-Project-Swiggy-Clone-App-Azure

![image](https://github.com/user-attachments/assets/431d52f9-e8f7-413d-882f-72e3f833ef3e)

For this project, I kept the source code in the Azure Repos as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/407318e5-7f71-40cd-bbb0-d237668f50ad)

The service connection has been created for Docker Registry as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/240a6536-eb13-48a7-ab13-d9a68e719e8d)

The screenshot for azure pipeline has been shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/9f5a75e4-2eb1-4b85-bf96-ca15b3eb2b78)

After runnging the Azure Pipeline the screenshot for SonarQube and swiggy app (ReactJS based User Interface which runs on port 3000) is shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/937c88f1-88c9-46e1-9662-0fadee4a4a0e)
![image](https://github.com/user-attachments/assets/de6d401a-fac3-4ff4-bf3e-fd312ebbd09b)

Entry for Azure DNS Zone is shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/1dc7d280-aa6e-4aaa-8402-217fd9665de6)

Finally we can access the swiggy clone app as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/831f9eb6-87ec-4742-bc0e-eb09d864c3db)


```
The swiggy-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry swiggy-clone-auth --docker-server=https://swiggycontainer24registry.azurecr.io --docker-username=swiggycontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX -n swiggy
```


<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:- https://github.com/singhritesh85/Swiggy-Clone-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://muditmathur121.medium.com/securing-swiggy-clone-app-deployment-on-aws-a-comprehensive-guide-to-building-a-devsecops-pipeline-67bdd7ea004e
```
