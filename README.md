# **GCP 6.5 Project Documentation**

# **Project overview :** Web Server Infrastructure with Load Balancing.

## - Project goals: _The project aims to ensure the high availability and resilience of the web infrastructure to handle unexpected server failures, while also focusing on scalability by designing the infrastructure to easily scale horizontally to accommodate increased traffic. Additionally, implementing a load balancer will evenly distribute incoming requests across multiple web servers, enhancing the system's efficiency and reliability. Security best practices will be implemented to protect the web servers and minimize vulnerabilities, while monitoring tools will be set up to track the performance and health of the infrastructure, ensuring proactive management and timely resolution of any issues._

# -**Set up steps:**

## Step 1 : Authenticate and Set Project.

gcloud auth login

gcloud config set project pistis-gcp-training

## Step 2: Create a VPC

![Screenshots](https://github.com/TolueneT/GCP-6.5-Project/blob/master/assets/images/vpc1.JPG)
![vpc1](https://github.com/TolueneT/GCP-6.5-Project/assets/163625665/269db915-5055-4eaf-8022-15f05049b601)


## Step 3: Create Subnets

### -Create Private Subnet

![Screenshots](images/subnet.JPG)

### -Create Public Subnet

![Screenshot](images/subnet2.JPG)

### -Create Firewall Rules

![Screenshots](images/firewall.JPG)

## Step 4: Create VM Instances

### -Create VM Instances

![Screenshots](images/vms.JPG)

### -Install Web Server Software

![Screenshots](images/web.JPG)

## Step 5: Set Up the Load balancer.

### -Create an Instance Group

![Screenshots](images/instance.JPG)

### -Create a Health Check

![Screenshots](images/health.JPG)

### -Create a Backend Service

![Screenshots](images/backend.JPG)

### -Add the Instance Group to the Backend Service

### -Create a URL Map

### -Create a Target HTTP Proxy

### -Create a Global Forwarding Rule

![Screenshots](images/last.JPG)

## Step 6: Enable Auto-scaling

### -Create a managed instance group

![Screenshots](images/managei.JPG)

### -Set Autoscaling

![Screenshots](images/autoS.JPG)

### - Deploy and verify depolyment

### - Check Autoscaler

![Screenshots](images/checkauto.JPG)
