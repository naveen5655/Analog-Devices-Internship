# Analog devices Internship Report ( Badisa Naveen)

Note: All rights reservered for Analog Devices, I took screenshots to explain my proect.

## Introduction 
Occasionally, our team gets tickets to restart a Jenkins controller that 
are crashed or broken because of a Java heap exception. Jenkins does provide 
an endpoint (`/restart`) for restarting itself but that won't be usable on 
a hung/broken controller. 
In order to fix the problem, the containerized Jenkins controller needs to 
be removed and redeployed. There is one issue though; our SWES team is 
EU/AS based and users from later time zones than users have to wait until 
we are back online to fix the issue. 

We have come up with a solution to this: Jenkins API User Interface. 

Our team worked hard to implement a user interface for Jenkins API for 
allowing users to restart their own Jenkins controller. With Jenkins API 
UI, you can do this by simply clicking on a restart button. Therefore, the 
dependency on other people and time zones is no longer an issue. 

# Jenkins API UI 
- I worked on Jenkins API UI project during my one year internship in Analog devices. 
- Technology used Angular and Golang.

## Home page
![image](https://github.com/naveen5655/Resume/assets/89301294/544c85c5-6d60-4244-a800-bd2600ded5e1)

![image](https://github.com/naveen5655/Resume/assets/89301294/bf6ff68a-eded-4aa9-b886-3fc74e5cc4cd)

![image](https://github.com/naveen5655/Resume/assets/89301294/8059a980-67bc-4394-adc4-00f001d79a65)

click on my controllers, it will redirect to this page:
![image](https://github.com/naveen5655/Resume/assets/89301294/c2992f8a-c0cc-44d6-ac93-abaa82863eb9)

select controller which you want to restart
![image](https://github.com/naveen5655/Resume/assets/89301294/01260d2c-d89b-43b2-b796-12fd8f0de6a1)

All selected turn into yellow color, we need to wait till 10 mins to restart again
![image](https://github.com/naveen5655/Resume/assets/89301294/28751c16-b8cb-48d9-9d58-bb92892db0ab)

# Admin view

![image](https://github.com/naveen5655/Resume/assets/89301294/586021a9-7f2d-4732-b618-3cb70fa21333)

click on upgrade banner
![image](https://github.com/naveen5655/Resume/assets/89301294/569c759e-3c38-4b5c-aa19-cb0507d81dc5)

After it look like this :
![image](https://github.com/naveen5655/Resume/assets/89301294/ef81a4ea-a789-40ed-b822-d08ff465bf99)

click on manage controllers:
![image](https://github.com/naveen5655/Resume/assets/89301294/80bd0e2e-82a6-416a-b02a-1a258587d49c)

click on add controllers:
![image](https://github.com/naveen5655/Resume/assets/89301294/8baad735-4678-4b9d-a549-b0d1961ec453)

controller added successfully:
![image](https://github.com/naveen5655/Resume/assets/89301294/4bef6bd0-2673-4429-9556-9bd7e4ce91f0)

we can filter the table based on dropdown:
![image](https://github.com/naveen5655/Resume/assets/89301294/1a20df50-e2f9-4fce-b2f4-512435c9eba4)

Jenkins API UI - Under the hood!
If you are curious about the underneath mechanism of Jenkins API UI, you can have a look at the following diagram which presents the whole process of restarting a controller:

![restart-flow](https://github.com/naveen5655/Resume/assets/89301294/18c76605-6c2f-44f1-b792-45e9d9b6c7b6)

### Thank you
