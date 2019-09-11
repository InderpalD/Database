# Microsoft SQL Server

MSSQL is a Relational Database Management System (RDMS)
SQL is used as the language to communicate with MSSQL

## SETUP

I am using my macbook and there is no MSSQL download for Macs. 
So I am using a docker image to run the SQL server.

In Docker Image for MSSQL:
Make sure you add the ENVIORNMENT VARIABLES ACCEPT_EULA and SA_PASSWORD
Under Hostname/Ports, make sure the docker port is the same as localhost port 
for connection

In some management studio (im using SQLPRO on Mac)
connect to localhost as server host with your docker container running. 

Boom, all set
