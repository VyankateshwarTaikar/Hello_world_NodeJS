# Design the IaC (Terraform, Aws ECS/Fargate) for Hello world Node.js app, CD pipeline using GitHub Actions
 
Hello_world_Nodejs_app 
1) Diagram for Design 

![1-diagram for hellow world](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/7874e2db-d3d9-4395-8259-47cf6cb2c028)


2 ) Flow for Design 

![Untitled Diagram](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/3b50943c-26eb-414e-9451-31b0bfa29f23) 


Find out required Application and infrastructure files here 👇 
🔗 https://github.com/VyankateshwarTaikar/Hello_world_NodeJS.git 

### Note: I am hiding ID & passwords form files & removing after runs the Hello world application

## Requirement/ prerequisite
1. AWS Account
2. VS code with installed & configured with terraform & git in windows 10


# Steps 
---------------------------------------------------------------------------------------------
# 1  
## Creating IAM USER and configuring Permissions 

Go the your AWS account and Follow the Steps.
![Screenshot_1](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/17f9c014-cb56-4eb6-80de-e5a4bced67b2) 

![Screenshot_2](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/c47ad414-f19b-45f4-941c-3e8b901a3fe5)


![Screenshot_3](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/ccc8595a-74c9-45e0-b240-3c1465199304)





![Screenshot_4](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4b89f7f0-92d8-4a95-af84-a557a14c4f0a)






![Screenshot_5](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5bed3685-adba-4074-a706-251c74b9ded2)

Note: Download .Csv File and keep it Secure . 


# 2  
## Configure Terraform files & create AWS Infrastructure 
VS code installed & configured with terraform & git in windows 10   -- As as prerequisite

Creating terraform files 

![Screenshot_5](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5bed3685-adba-4074-a706-251c74b9ded2)

---------------------

![Screenshot_6](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/cc8b8b36-a5bb-4d06-ac1c-61d4021edc82)



![Screenshot_6_1](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/29a168b6-e66e-479a-9a72-154e4f79a454)







![Screenshot_7](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/1cf1e7a1-1d11-4b13-875b-777fdff6ad36)

![Screenshot_8](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/02125353-3df1-4f95-a58b-5c453d85a969)


![Screenshot_9](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4a656f42-d56a-46e3-b0e6-94e7aadd154f)



![Screenshot_10](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/310153d1-7906-455d-b570-f63014807975)


Check with AWS Account for VPC is created or not. 

![Screenshot_11](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/3039cf2d-9ba6-4787-afdc-287d997ae99e)

Now , Create subnets so edit vpc.tf 

![Screenshot_12](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5b58ad30-2882-40df-856c-1f8d590c899c)



![Screenshot_13](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/a41fb682-248f-4f60-80e3-a4e39d5a05f2)




![Screenshot_14](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/de0c54dd-29a8-4d5f-b662-0b8dd78ad3a5)



![Screenshot_15](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/9af84398-2b77-4949-999c-e2fec34e0367)




![Screenshot_16](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4b0699d0-063e-4529-b9a1-8bcd15c5ea7e)



![Screenshot_17](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/df284453-1d4e-4575-b3f0-88cc5ffd99ad)


![Screenshot_18](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/2453e506-bf1e-45da-8a5c-6213fd4ea635)

![Screenshot_19](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/e289c45f-f7bc-403e-8e36-0bdefa85915c)


Check with subnets are created not .

![Screenshot_20](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/8b8a9923-738f-4277-9dce-87905781c334)













