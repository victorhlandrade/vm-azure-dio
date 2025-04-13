# vm-azure-dio
DIO Challenge – Creating Virtual Machines on Azure.

I will demonstrate step by step how to create virtual machines on Azure. In this activity, I chose to set up a multi-zone environment and use the load balancing feature to ensure high availability.

Step 1 – Select the hamburger menu > Virtual Machines > Create > Azure Virtual Machine.
img1.png

![Image](https://github.com/user-attachments/assets/e04d6f55-3b91-4be0-b2b7-626807b0d073)

Step 2 – I entered the name of my VM and kept the default region.

![Image](https://github.com/user-attachments/assets/44aedc4c-e90e-4d84-9d4b-b1fd0ab1cfe2)

Step 3 – I then selected the availability zone I wanted to use. I chose all three zones in my region to ensure greater service availability. I kept the default security settings recommended by Azure and selected an Ubuntu Linux 22.04 LTS virtual machine.

![Image](https://github.com/user-attachments/assets/51a55b1c-fdbb-4f16-b3b7-d74389d82b9a)

Step 4 – Here you can change the size of your virtual machine. I chose to keep the size recommended by Azure.

![Image](https://github.com/user-attachments/assets/2533207c-af3d-4273-a7a3-a412026a03fa)

Step 5 – In this step, I kept Azure's default settings.

![Image](https://github.com/user-attachments/assets/ad33c07a-70b9-4b89-9b94-fd2be7251d87)

Step 6 – In Networking, define your subnet and the address space to be used. We will use the default settings provided by Azure.

![Image](https://github.com/user-attachments/assets/94660d67-6292-470a-916d-352756c1d024)

Step 7 – Since we chose multiple availability zones, we will create a load balancer to distribute the incoming requests.

![Image](https://github.com/user-attachments/assets/9ad60a13-1b5e-4d78-828d-890ce61e7e9a)

Step 8 – Here we define the name of the load balancer and keep the other options as default.

![Image](https://github.com/user-attachments/assets/12d80495-b803-40cd-96da-ffe1c3730408)

Step 9 – We keep the default options and select the newly created load balancer.

![Image](https://github.com/user-attachments/assets/8e6c1d4c-f5dd-4e4c-8bd4-3df6e01ab041)

Step 10 – Keep the remaining options as default and click Review + Create.

![Image](https://github.com/user-attachments/assets/812df5a8-8822-41c8-89dc-a1d892bce338)

Step 11 – Confirm the validation of the settings and click the Create button.

![Image](https://github.com/user-attachments/assets/47c89774-3dda-4c73-86ec-2391f66f4b00)

Step 12 – Download the SSH key and continue with the installation.

![Image](https://github.com/user-attachments/assets/3f4b8d24-7743-4556-88ac-babb348faa83)

Step 13 – Wait for the installation to complete.

![Image](https://github.com/user-attachments/assets/ea093fa0-c3e9-41e1-9b76-baa1fb99ba0a)

Step 14 – Congratulations, the installation was completed successfully.

![Image](https://github.com/user-attachments/assets/75c2301b-dde8-474b-95ca-96a76f12be50)

Step 15 – View your VMs in the Azure dashboard.

![Image](https://github.com/user-attachments/assets/9e2ccdad-52f5-4bbf-be44-11cbb86937fb)

Step 16 – After removing your virtual machines, also remove the resources to avoid future charges.

![Image](https://github.com/user-attachments/assets/4d8e5847-2e41-4bbc-9c30-5304664544db)
