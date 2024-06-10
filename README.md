# AWS-Amplify_Math_power
Main Service Used: Aws Amplify
Other Service Used: Lambda, Api Gateway, DynamoDB

Files_Description:
index.html: it contain the html code for the website to render
lammda_fucntion: it has the python code for the lamda function, it calculate the power of 2, and also store the result in table of DynamoDB
policy: It is a policy for the lambda role , to access the DynamDB

WorkFlow:
Amplify->upload index.html in zip -> make api-> connect api to lambda-> give role to lamda to access dynamodb-> make dynamodb table
