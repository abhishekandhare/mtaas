

# MTAAS



## Usage

To connect to the database edit the mysql.js file in routes folder with the local host user name and password.
The Create Table Execution Statements file has the table queries which can be used to execute the table queries on localhost.

## Developing

##Description
A MEAN Stack SAAS application deployed in Amazon EC2 Bitnami Instances with RDS MySQL Database with Auto Scaling, Load Balancing and Multi Tenancy for Mobile Crowd Test Sourcing. The following project can be deployed on any Bitnami Instances on Amazon EC2 and the Database Required is Amazon RDS MySQL. The required tables can be created using the Create Table Execution Statements file.

*Autoscaling: You'll have to enable Autoscaling while deployment in Amazon EC2 across the Instances required.
*Load Balancing: Amazon Elastic Load Balancer can be used to Balance the Load between the various Instances of the Amazon EC2 Bitnami Instances.
*Multi-Tenancy : Please deploy two separate Load Balancers for four different Instances of the Application.




