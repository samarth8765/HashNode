# Practical applications of IAAS, PAAS and SAAS

- In this article I'm not explaining what is IAAS, PAAS or SAAS, rather I'm pratical demonstrating the differences among them.

## IAAS
- IAAS or Infrastructure as a service provides infrastructure for our product like networking, storage, servers, virtualization.

- Other infrastructure aspects are managed by developers like OS, Middleware etc.

- The best example for understanding IAAS is Amazon EC2 machine.
<p align="center">
    <img src="./images/./images/IAAS.png">
</p>    

### So what is Amazon EC2?
- AWS EC2 or Elastic Compute Cloud is a IaaS provided by amazon which works on pay-as-you-go model. EC2 allows users to rent virtual computers on which to run their own computer applications.

- In simple terms, it is an enviroment provided by amazon which we can access through internet.


- Now let us see how it works -
    - __How to create an EC2 instance ?__
    - You can skip this part if you know how to create a EC2 instance.
    - First step is to signin or signup in [AWS](aws.amazon.com).
    <p align="center">
    <img src="./images/AWS_login_page.png">    
    </p>  
    - Search ec2 in the search bar and click on the first option i.e EC2.
    <p align="center">
    <img src="./images/EC2_dashboard.png">    
    </p>  
    - This is EC2 dashboard. To create a new EC2 instance click Launch instance.
    <p align="center">
    <img src="./images/launch_instance.png">    
    </p>  
    - Now let us create our EC2 instance.<p>
        - Name your EC2 instance like demo_server (optional).<p>
        - Select OS you want to work with. For the sake of simplicity I'm selecting Ubuntu OS because it is familier with most of us.<p>
        <p align="center">
        <img src="./images/name_os_selection.png">
        </p>
        - Select t2.micro as instance type.<p>
        <p align="center">
        <img src="./images/instance_type.png">
        </p>        
        - For accessing the EC2 machine, we need a key-pair.Create a new-key pair.
        <p align="center">
        <img src="./images/create_key.png">
        </p>
        - A key will be downloaded .<p>                
        - Now click on launch instance.
        <p align="center">
        <img src="./images/launching_instance.png">
        </p>        
        - Our instance is running on AWS. Click on connect to connect with our EC2 machine.
        <p align="center">
        <img src="./images/connect.png">
        </p>
        - Follow the below steps to connect via SSH client.
        <p align="center">
        <img src="./images/SSH_client.png">
        </p>
        - Yay, we have successfully connected to our EC2 machine.
        <p align="center">
        <img src="./images/EC2_machine.png">
        </p>
        - We can run or host any server on our machine like a node or a python
        application but cloning a project from a remote repo like github.<p>
        - So this machine is an IaaS because a developer has to care about creating and maintaing OS, data, middleware as well as code for application.


## PaaS
- 
