# OSProject

Members: <br>
IRFAN BIN AMRAN <br>
NUR AIENA HAJEERAH BT ABDUL HAKIM <br>
NUR SYAZWANI BINTI JAMALUDIN <br>
SITI NUR ABILAH BINTI KASIRIN <br>

Lecturer Dr. Rizal Bin Mohd. Nor


<br>
<br>
<br>
Next, We will download the docker application, with the link : https://docs.docker.com/desktop/windows/install/ <br>

How to start running docker: Search docker on your desktops and click the docker, The docker will ask you to accept the term and you need to accept the term to continue.
<br>
First, after you accepted the terms and click on continue, you will see the interface of docker , then you just follow the tutorial if you are new to this apps,eitherwise you can skip if you already know how use it. <br>

![image](https://user-images.githubusercontent.com/82078205/174483386-f52321c0-c9bd-4541-b554-914c010af20c.png)
<br>
<br>

Second, click start and the clone pages will show up, click next step to proceed to the next page.<br>
![image](https://user-images.githubusercontent.com/82078205/174483460-7ce27c74-6f92-4c96-9e65-16e861feb9a1.png)
<br>
<br>
Give permission to the docker by allowing windows firewall to give full access to the docker and click allow access. then proceed to click next step in the 3 page after you give permission top docker. <br>
![image](https://user-images.githubusercontent.com/82078205/174483502-0e5e346b-baba-4b9d-b2d9-f67180456e45.png)
<br>
<br>

Next we will install WSL2, from the link: https://aka.ms/wsl2kernel <br>
<br>
Once done installing the package, click on finish, restart your system and then you can run docker.
<br>
<br>

How to use docker: <br>
<br>
First step, open the docker application:<br>
![image](https://user-images.githubusercontent.com/82078205/174483684-e93fdca1-d426-4085-a4d6-3f926f48ee16.png)
<br>
Secondly on the docker home menu, look for Mongo<br>
![image](https://user-images.githubusercontent.com/82078205/174483773-a88913c9-c1b7-4ad9-9f78-2561412d5872.png)
<br> 
Make sure a connection to the internet is available and click run.<br>
<br>
<br>
On the images page, there we can see the progress bar for the run.<br>
Once Mongo is done running, we can see the docker image mongo in the application<br>
![image](https://user-images.githubusercontent.com/82078205/174483870-523f8158-2565-4338-afd5-5009ae49ce68.png)
<br>
and when it says that it is in use, that means that it is running appropriately. <br>
<br>
<br>

Once all of the installations are done we can start the next step to start a docker container and create a MongoDB container the MongoDB. <br>
<br>
Firstly, to start MongoDB container in docker we can use the command in PowerShell <br>
![image](https://user-images.githubusercontent.com/82078205/174483979-1eb51ede-f42d-47d6-b97a-c4ec93fab66c.png)
<br>

In the PowerShell, type in <br>
“ docker run -d -p 82:82 --name group-6-operatingsystem mongo:latest “
<br>
And if no error shows up, that means a container is successfully created. <br>
<br> On the Docker application, we can see that a new container has been created in it. <br>
<br>









