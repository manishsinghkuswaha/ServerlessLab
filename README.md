# ServerlessLab
A CRUD (Create, Read, Update, Delete) operations project using API Gateway, AWS Lambda, and DynamoDB involves several steps. In this project we build a RESTful API that interacts with a DynamoDB table to perform CRUD operations on items in the table.
Below is the high level design:
![high-level-design](https://github.com/manishsinghkuswaha/ServerlessLab/assets/47105557/05bf3923-9df5-452d-9246-ae37d8f03513)
The POST method on the DynamoDBManager resource supports the following DynamoDB operations:

* Create, update, and delete an item.
* Read an item.
* Scan an item.

## Setup

### Create Lambda IAM Role 
Create the execution role that gives your function permission to access AWS resources.

To create an execution role

1. Open the roles page in the IAM console.
2. Choose Create role.

### Create Lambda Function
![lambda-code](https://github.com/manishsinghkuswaha/ServerlessLab/assets/47105557/b86e84d5-42ac-4104-985f-5c82035bfc50)

### Create DynamoDB Table
### Create API
### Deploy the API
