## **DEPLOY 'IBM DATA POWER' IN POSTMAN (SCRIPT: .sh)**

**1. CONTEXT:**
*"Software automation is very important, especially in scenarios where many known steps can be unified so that they are executed sequentially."*
<p> </p>
<p> </p>

**2. USE CASE:**
Currently, clients require having environments installed quickly and to do so it is necessary to implement **SANDBOX** environments that meet this requirement.

Because of this, there is a need to know how to automate the installation of such **SANDBOX** environments, in a way that does not impact the client's environment and is quick to execute. 
<p> </p>
<p> </p>

**3. SOLUTION:**
The working solution is based on the development of a **IBM DATA POWER**  **SCRIPT** in **.sh** that covers the following points: 

1. PARAMETER CONFIGURATION.
2. METHOD CONFIGURATION.
3. TESTING DEPENDENCIES.
4. TESTING CONNECTION.
5. REMOVING EXISTING CONTAINER COMPONENTS.
6. DOWNLOADING IMAGE.
7. APPLYING TAG.
8. DEPLOYING CONTAINER.
9. VALIDATE LOGs.
10. VALIDATE URL.

This **Script** has been deployed on a **VM** in **IBM-CLOUD** (reusing many of the base Infrastructure components such as: **FLOATING-IP** ).  
<p> </p>
<p> </p>

**4. EJECUCIÓN:**
To test you need to run:

` $ dos2unix Instal-ACE (PODMAN) - Linux.sh`
` $ chmod 777 Instal-ACE (PODMAN) - Linux.sh`
` $ sh ./Instal-ACE (PODMAN) - Linux.sh`
<p> </p>
<p> </p>

**5. IMAGES:**
Several images associated with the execution and result obtained are shared:

Detail of **Script**:
![alt text](https://github.com/maktup/SCRIPT-FOR-DEPLOY-IBM-DATA-POWER-IN-POSTMAN/blob/main/images/1.jpg?raw=true)
<p> </p>
<p> </p>
 
**Script** executed:
![alt text](https://github.com/maktup/SCRIPT-FOR-DEPLOY-IBM-DATA-POWER-IN-POSTMAN/blob/main/images/2.jpg?raw=true)
<p> </p>
<p> </p>
  
**Web-UI** Activated:
![alt text](https://github.com/maktup/SCRIPT-FOR-DEPLOY-IBM-DATA-POWER-IN-POSTMAN/blob/main/images/3.jpg?raw=true)
<p> </p>
<p> </p>

**Dashboard** loaded:
![alt text](https://github.com/maktup/SCRIPT-FOR-DEPLOY-IBM-DATA-POWER-IN-POSTMAN/blob/main/images/4.jpg?raw=true)
<p> </p>
<p> </p>

**6. SOURCES:**
All fonts can be downloaded and reused here: [https://github.com/maktup/SCRIPT-FOR-DEPLOY-IBM-DATA-POWER-IN-POSTMAN.git]
