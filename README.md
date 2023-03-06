# Virtual-Networking
Deploy a cloud server for a security team to test a vulnerable web application.

# Goals
1. Azure requires you to create a resource group before you can set up anything else. 

    - Create a resource group that will contain everything the Red Team needs in the cloud.
    
		- Note: Choose the region you determined in the class walkthrough.  Every resource you create going forward must be created in the exact same region.		

2. Before you can deploy servers and services, you must have a network where they can be accessed. 

    - To create a new VNet, search the Azure portal for "virtual network" and launch the Virtual networks page.

3. Use the **+ Add** button to create a new network. Use your networking knowledge to fill in the correct fields.

    - Note: Choose a region that you can easily remember. Every resource you create going forward must be created in the exact same region.
![add_network](Images/add_network.png)
4. For your network, set the following criteria and configurations: 

    - A descriptive name, so this VNet can't be confused with other cloud networks on the account.

    - Subscription type.  
    
    - The resource group you created in step two.
    
    - The same location you chose for your resource group. 
    
    - Use the default network and subnet definitions in the IP Addresses section.

    - Use the default settings for Security.

      - In order to avoid recurring charges, do **not** enable DDoS Protection Standard.

    - No tags are needed.
