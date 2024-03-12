AWS Fargate & ECS Fundamentals

** Step-01: Clusters Introduction **

![image](https://github.com/chrahul/ECS_to_OCI/assets/14847377/ae820ab9-95b9-490b-afcc-003007687b8d)


# Step-02: Pre-requisite

Before getting started with ECS clusters, ensure the following prerequisites are met:

- **VPC Details:**
  - Name: ecs-vpc
  - IPV4 CIDR Block: 10.0.0.0/16

- **Subnets:**
  - Name: ecs-public-1a, CIDR Block: 10.0.10.0/24
  - Name: ecs-public-1b, CIDR Block: 10.0.20.0/24

- **Internet Gateway:**
  - Name: ecs-vpc-igw

- **Route Tables:**
  - Associate a public route for the main route table.

# Step-03: ECS Cluster Types & Create a Cluster

In this step, we'll explore the different types of ECS clusters and create one.

## Cluster Types

We have three types of clusters:

1. **Fargate Cluster (Serverless)**
2. **ECS EC2 - Linux Cluster**
3. **ECS EC2 - Windows Cluster**

## Create a Cluster

Follow these steps to create an ECS cluster:

1. Navigate to the ECS Service.
2. Click on Clusters.
3. Choose the type of cluster you want to create (Fargate, ECS EC2 - Linux, or ECS EC2 - Windows).
4. Provide the necessary details such as cluster name, VPC, subnets, etc.
5. Complete the cluster creation process following the on-screen instructions.

