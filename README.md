# hcl_repo

The complete prototype build using two AWS  technology:
1- AWS RDS 2- AWS LAMBDA function to deploy our code(attached zip file to import into lambda function)
This solution zip file has two dependencies and one main function as below.1- pymsql2- PyMySQL-0.8.0.dist-info3- main.py
information:main.py functionality:- function connects with the RDS database and create a table. after that it insert the json data from test event and stores into relational database AWS RDS.
Database_name = hcl_dbuser_name= hcl_admintable = test_tbRDS_hostname = hcl-usecase.ckqip1nhihss.us-east-2.rds.amazonaws.comPassword = **********
Json data triggered as an test event as below :{
  "id": "3",
  "name": "manuj"
}
