# Simple-Website-Hosting-using-AWS-EC2 

### Step 1 : Firstly Create an AWS EC2 Instance by clicking Launch Instance

 ![Screenshot 2024-07-17 170403](https://github.com/user-attachments/assets/3839698e-4b7f-4a9a-8350-7ecccbce164a)


### Step 2: Then configure your EC2 Instance 

1. Give the name of your EC2 instance  

![Screenshot 2024-07-17 170428](https://github.com/user-attachments/assets/628d24a8-f812-4a13-8f78-b4248642ed71)

2. Choose the AMI you are going to use 

![Screenshot 2024-07-17 170459](https://github.com/user-attachments/assets/db390166-ad99-4d9b-af74-a1fb69942333)
 

3. Create your private key pair

![Screenshot 2024-07-17 170544](https://github.com/user-attachments/assets/f6e1e40c-599b-43fc-bc74-5ad7443016f6)


4. Configure your security group 

![Screenshot 2024-07-17 170630](https://github.com/user-attachments/assets/4a105970-36a9-4768-99e8-eed6c2aedb9e)


5. Now let us launch our instance by clicking "Launch Instance" and then our Instance will be launched

![Screenshot 2024-07-17 170724](https://github.com/user-attachments/assets/2bc2c846-3414-4611-92e2-06a932578663)


### Step 3: Install Apache Web Server in EC2 

1. Let us copy the public IP of our EC2 Instance

![Screenshot 2024-07-17 171020](https://github.com/user-attachments/assets/c2a595cd-5950-473d-a2a7-c09b37cf50c0)


2. Now let us open PuTTy and put our public IP and private key pair so that we can access our EC2

![Screenshot 2024-07-17 171050](https://github.com/user-attachments/assets/3b7d633a-e0d5-40ae-817c-902e1f06315e)


![Screenshot 2024-07-17 171126](https://github.com/user-attachments/assets/4dc3c616-e379-483a-bba4-67678416a781)


3. Now let us switch into root user using command:

![Screenshot 2024-07-17 171247](https://github.com/user-attachments/assets/e710db0a-1bba-4ff3-aad3-5596596c2177)


4. Now let us install the Apache Webserver using command:


![Screenshot 2024-07-17 171326](https://github.com/user-attachments/assets/d20a4564-640d-4d63-b528-0cdac2ca9ddd)


5. Now let us check the status of our Webserver using command: 


![Screenshot 2024-07-17 171358](https://github.com/user-attachments/assets/0b0a0279-c535-4656-b53e-970440e5e567)


6. Now let us enable and start our Webserver using command:


![Screenshot 2024-07-17 171450](https://github.com/user-attachments/assets/b027cfb8-5dfb-4d5b-bb03-d6df7258e846)

7. Now if we put the public IP of our EC2 Instance in browser we get: 


![Screenshot 2024-07-17 171548](https://github.com/user-attachments/assets/25112e1d-f578-4e11-95a7-538c1bc2fb16) 


![Screenshot 2024-07-17 171559](https://github.com/user-attachments/assets/6f2f7179-7553-4853-8349-847242049bbe)


### Step 4: Put our files into the WebServer

1. Now inorder to put our files in our webserver we have our directory here

![Screenshot 2024-07-17 171641](https://github.com/user-attachments/assets/a6ac7e1b-9108-4a97-b5ed-b87b664814e3)

2. Now let us give permissions for our directory to read and write using command:

![Screenshot 2024-07-17 171710](https://github.com/user-attachments/assets/23124a7d-6289-4fbd-81cc-93ac2a3e5670)

3. We use WinSCP to login into our EC2

![Screenshot 2024-07-17 171800](https://github.com/user-attachments/assets/d181997a-fcc6-484a-9bf4-bbfcd25a899a)

4. Now let us change the directory to /var/www/html/

![Screenshot 2024-07-17 171836](https://github.com/user-attachments/assets/c6101ce3-0b28-4409-b32f-e3d142d8c484)

5. We can now paste our index.html file and save it


![Screenshot 2024-07-17 171930](https://github.com/user-attachments/assets/587adcbd-818c-4247-bdab-43eb11e10728)


![Screenshot 2024-07-17 171945](https://github.com/user-attachments/assets/c1211e33-4c2c-4073-b4ce-fb8316026ca9)

### Step5: Check if the website is hosted 

Open the browser and paste the public IP of our instance as URL and you will see: 

![Screenshot 2024-07-17 171957](https://github.com/user-attachments/assets/425ac924-57a0-498f-b93f-a027364e7000)


   













