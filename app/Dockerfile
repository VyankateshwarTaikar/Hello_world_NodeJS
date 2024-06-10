FROM node:19.6

WORKDIR /app

COPY package*.json ./
RUN npm install
COPY .. ./
CMD node index.js





#   Now we Have to create a " .github ""  diretory where the inside that 
#   there we have to create workflows diretory 
#   inside that .yml file have to create having a name " aws.yml " and onther one is td.json
#   taskDefination.json A task definition is a blueprint for your application.
#   It is a text file in JSON format that describes the parameters and one or more containers 
#   that form your application

#   .github > workflows > -----> aws.yml
#                         -----> td.json


#    Now you can check it out as a task defination where versions you can check.
#    so go to latest one and copy JSON 
#    Amazon Elastic Container Service > Task definitions > app >  Revision1 >JSON


#    Now , Go to the aws.yml and write a configuration for push and enviroment variables
