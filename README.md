# Design the IaC (Terraform, Aws ECS/Fargate) for Hello world Node.js app, CD pipeline using GitHub Actions
 
Hello_world_Nodejs_app 
1) Diagram for Design 

![1-diagram for hellow world](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/7874e2db-d3d9-4395-8259-47cf6cb2c028)


2 ) Flow for Design 

![Untitled Diagram](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/0eb82fb2-328b-4b01-b090-5a48bf9d2ff1)



Find out required Application and infrastructure files here 👇 

🔗 https://github.com/VyankateshwarTaikar/Hello_world_NodeJS.git 

### Note: I am hiding ID & passwords form files & removing after runs the Hello world application

## Requirement/ prerequisite
1. AWS Account
2. VS code with installed & configured with terraform & git in windows 10


# Steps 
---------------------------------------------------------------------------------------------
# 1  ======>>   ======>>    ======>>   
## Creating IAM USER and configuring Permissions 

Go the your AWS account and Follow the Steps.
![Screenshot_1](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/17f9c014-cb56-4eb6-80de-e5a4bced67b2) 

![Screenshot_2](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/c47ad414-f19b-45f4-941c-3e8b901a3fe5)


![Screenshot_3](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/ccc8595a-74c9-45e0-b240-3c1465199304)





![Screenshot_4](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4b89f7f0-92d8-4a95-af84-a557a14c4f0a)






![Screenshot_5](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5bed3685-adba-4074-a706-251c74b9ded2)

Note: Download .Csv File and keep it Secure . 


# 2    ======>>   ======>>    ======>>   
## Configure Terraform files & create AWS Infrastructure 
VS code installed & configured with terraform & git in windows 10   -- As as prerequisite

Creating terraform files 

![Screenshot_5](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5bed3685-adba-4074-a706-251c74b9ded2)

---------------------

![Screenshot_6](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/cc8b8b36-a5bb-4d06-ac1c-61d4021edc82)



![Screenshot_6_1](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/29a168b6-e66e-479a-9a72-154e4f79a454)



^^  Scrects considering for only this deployment 



![Screenshot_7](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/1cf1e7a1-1d11-4b13-875b-777fdff6ad36)

![Screenshot_8](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/02125353-3df1-4f95-a58b-5c453d85a969)


![Screenshot_9](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4a656f42-d56a-46e3-b0e6-94e7aadd154f)



![Screenshot_10](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/310153d1-7906-455d-b570-f63014807975)


== > Check with AWS Account for VPC is created or not. 

![Screenshot_11](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/3039cf2d-9ba6-4787-afdc-287d997ae99e)

Now , Create subnets so edit vpc.tf 

![Screenshot_12](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5b58ad30-2882-40df-856c-1f8d590c899c)

![Screenshot_21](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/cd4253bf-c3cf-47a8-81e7-a7c304b24c52)

![Screenshot_13](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/a41fb682-248f-4f60-80e3-a4e39d5a05f2)




![Screenshot_14](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/de0c54dd-29a8-4d5f-b662-0b8dd78ad3a5)



![Screenshot_15](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/9af84398-2b77-4949-999c-e2fec34e0367)




![Screenshot_16](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/4b0699d0-063e-4529-b9a1-8bcd15c5ea7e)



![Screenshot_17](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/df284453-1d4e-4575-b3f0-88cc5ffd99ad)


![Screenshot_18](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/2453e506-bf1e-45da-8a5c-6213fd4ea635)

![Screenshot_19](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/e289c45f-f7bc-403e-8e36-0bdefa85915c)


== >Check with subnets are created or not & verify with subnetID

![Screenshot_20](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/8b8a9923-738f-4277-9dce-87905781c334)


# 3    ======>>   ======>>    ======>>   
## Creating repository terraform file and Check with repository in AWS


![Screenshot_27](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/9cb3398c-f888-44b5-9412-0e2986c02965)






![Screenshot_28](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/d0347288-b8f3-48a1-bb87-e2a509abbdf0)




![Screenshot_29](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/09a63f85-4de0-4030-acfd-09b2e77c3429)




![Screenshot_30](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/1388638d-e67d-4221-a034-717acb6d8f5b)


![Screenshot_31](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/954c571b-5337-4ae0-87bc-7af13d958c93)

![Screenshot_32](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/dc2a36fe-49db-4a83-b930-4768c370ce19)

## ==>Check With IAM role  from where note ARN and write in ecs.tf ,apply by terraform command and check with in AWS ECS.

![Screenshot_33](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/2dbe5faf-7894-4b9e-8080-39d73b17e7e5)

![Screenshot_34](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/5ae9d1c9-c79f-4de1-bd29-46ed9410f17f)


![Screenshot_35](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/a855f2a0-698d-4dee-844a-8251e0713824)

![Screenshot_36](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/f7efc3a0-f908-4c93-b4be-bb00cf03dec7)


![Screenshot_37](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/6452eeb5-f28e-48e4-af5a-d51b86a37cc2)


![Screenshot_38](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/eef34aa1-a525-42ad-8530-f694c043bc3a)

![Screenshot_39](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/d4481108-8c95-4ec4-bef3-2146e9b766f2)
![Screenshot_38](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/0c99606a-048c-4053-86b8-f5538cf1fd6b)

![Screenshot_40](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/32ed068d-23ed-4f4f-8a23-9d1dd1081db9)


![Screenshot_41](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/c3a220ff-9074-4a3c-914c-8181e7ed8e0f)

# 4    ======>>   ======>>    ======>>   
## Creating github workflows for actions 


![Screenshot_42](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/17b6e5ee-c445-463e-89b8-ef78c69cecc1)

![Screenshot_42_](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/9e7656b9-231d-41be-a83a-31505774ceac)


![Screenshot_42_1](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/1c0286d3-e88e-42fc-b87d-e10e411dc59a)

![Screenshot_43](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/d4286fe7-1930-481d-ad1f-55596839fff7)


![Screenshot_44](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/082072ff-ba75-4637-b588-d27c0b9463da)


![Screenshot_45](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/d313007c-6972-4419-bc63-4d107c971155)

![Screenshot_46](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/e7dc299f-fbca-4b69-8e77-dc1b4f010dca)

![Screenshot_47](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/48872df3-f974-4edd-8692-0cb7e5fba1e7)


![Screenshot_48](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/fb6840f1-3f3e-4347-a9ab-6a9abcea0fe3)

![Screenshot_49](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/ef8e1bd8-a8c6-4272-adc2-64430ff06dfa)

# 5    ======>>   ======>>    ======>>   
## Adding secrets as a AWS_ACCESS_KEY_ID  & AWS_SECRECT_ACCESS_KEY

![Screenshot_52](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/b20f2f3b-2e4e-4f3f-bc0e-5d155d558c62)


![Screenshot_53](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/a9b3ccdb-48e8-4372-ae0b-e2927757c72e)


# 6    ======>>   ======>>    ======>>   
## Access With the Application for Hello World 
As you Update the vpc.tf  it will automatically run the  Github actions. 
Add with Internet Gateway and Route Table 

![Screenshot_57](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/89b98ae6-eba7-4999-96d6-f0d100c216d1)

## ==> Go to the Actions tab where the our repository . you can check with running current Deployment.


![Screenshot_58](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/bcfacf41-cb5a-4274-917b-9fadaed7d0c7)

![Screenshot_59](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/2d9497d4-146c-4572-8966-108301def2d7)

![Screenshot_59_](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/83bcdb8b-f775-4db1-9e87-5b81c2054bd3)

![Screenshot_60](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/f40bb0d0-d41d-446b-af93-fa87b7b8615d)

![Screenshot_61](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/e9e6d519-6f87-445b-91f7-c890f1cc3efe)

![Screenshot_62](https://github.com/VyankateshwarTaikar/Hello_world_NodeJS/assets/102132721/e0cd6ebd-3964-4496-8502-c71632ccd1e1) 

Now , Remove the infrastructure from AWS Account.

# I've successfully launched the Hello World application with Node.js.   Thank you  !
