## Setting Up Resource Group

### Step 1

#### From the dashboard we can search for resource groups in the search bar. Click on Resource groups to create a new resource group.





![image2](https://user-images.githubusercontent.com/115432675/223289863-a527c45a-8f31-45c8-9864-b37ef01bd4a5.png)

<details>
  <summary>Click for Step 1 dropdown.</summary>
  
  <br>
  
1. Azure requires that you set up a resource group before you can set up anything else.
2. Use the Azure portal to create a resource group that will contain everything the development team needs.

</details>






![image10](https://user-images.githubusercontent.com/115432675/223291427-d9507fb8-787d-4237-870c-c2b327393701.png)

Click **+Create** button or the Create Resource Button








## Create a name for your resource group and choose a region. 

### Step 2

<details>
  <summary>Click to drop down step 2.</summary>
  
  <br>
 
1. Create name of your resource group and choose a region. 
2. Every resource you create after this must be created in the same region.
3. Click on **Review + create**
4. Go to resource groups in the top-right corner to view your new resource group
  
**Note:** When creating a resource group it is best practice to keep note of what region your group is in. This group's region is the East US, so I put EUS at the end of the resource group name (Exmple-Resourcegroup-EUS) for myself or whoever else is managing the server knows the region.
  
</details>


![image8](https://user-images.githubusercontent.com/115432675/223294082-f38e3513-056e-4ad2-aad7-3c168d09757d.png)




 - Azure will let you know if there are any errors. Click on **Create** to finalize your settings and create the group


![image7](https://user-images.githubusercontent.com/115432675/223298662-af6801a3-e7b4-46cb-88aa-bdf5493b9de2.png)

<details>
  <summary>Click to drop down step two.</summary>
  
  <br>
  

 
  

  
  </details>
  
  
  ![image5](https://user-images.githubusercontent.com/115432675/223300263-6f32b43f-fe1b-44fa-9a73-b811467ab879.png)
  
  
  
  ## Step 3: Setting up the VNet
  
  ### Before you can deploy servers and services, there must be a network where these items can be accessed. 
  
  #### It is important to make sure the network has any resources the group will need now and in the future.
 
 <details>
  <summary>Click to drop down for VNet set up steps.</summary>
  
  <br>
  
1. Return to the search bar and search network and **choose Virtual networks**
2. Click **+create** once in Virtual networks
3. IP adresses Keep Default
4. Keep security default we will secure our network with a security group later. 
5. Click **Create**
  
**Note:** tags will not need to be created
  
  </details>
  
  


![image8](https://user-images.githubusercontent.com/115432675/223301106-3fdc9312-0b31-412c-b93a-4b82218d7015.png)


![image3](https://user-images.githubusercontent.com/115432675/223302191-bfa47c42-9357-40b2-ab24-245ad91cc363.png)


![image11](https://user-images.githubusercontent.com/115432675/223302296-22d1590f-0121-4c6c-acdd-31fc32f1894e.png)


![image9](https://user-images.githubusercontent.com/115432675/223302681-2fe091b9-9fd1-4829-bfb2-54657d5089c8.png)


## Step 4: View what you have created!

 <details>
  <summary>Click to drop down for VNet set up steps.</summary>
  
  <br>
  
- Once you have created your resource group and VNet, return to the home screen and choose the resource group option
- See the list of Resource groups and click on the created resource group from the first step to find your virtual network.
- See your virtual network inside of your resource group
  
  </details>
  
  
  
  ![image6](https://user-images.githubusercontent.com/115432675/223303402-bd73f4d6-44a2-40de-85bd-f5d9822197b3.png)
  
  
  ![image4](https://user-images.githubusercontent.com/115432675/223303520-c83e5a72-75d5-4ad0-a63b-a02e140f406e.png)
  
  
  
