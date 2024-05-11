# AzureResource---Pulumi Infrastructure Deployment 
Example to create Azure Resource using Pulumi (Infrastructure as Code), in order to create basic yet complex azure infrastructure. Followimng are the list of resources getting created using this method 

1. azure resource group 
2. azure storage account 
3. enable static website for azure stoerage account  
4. add index and error html page 
5. enable azure cdn for static website 

##  Get Started 
1. Clone rep and move inside that directory 

    ``` bash 
    https://github.com/Shatabdi2621/AzureResource---Pulumi.git
    ```
2. Compile the project and install all the dependenies 
3. Check az log-in the command prompt, & then check integration of Pulumi with your local machine 
4. Move inside MyStack.cs 
5. Execute the following commands 
    ``` bash 
    pulumi preview 
    ``` 
    To preview the list of resources getting created using the MyStack.cs 

    ``` bash 
    pulumi up 
    ``` 
    To deploy the infrastructure over the azure cloud account 

    ***Optional***
    ``` bash 
    pulumi destroy 
    ``` 
    To destroy the infrastructure created if you need to make any modification or created for testing purpose 

**Primary Requiremnets for the project**
- azure cloud account with login, connected to your system
- pulumi account with login, connected to your system 
- azure cli 
- pulumi cli 