# java-web-maven-dropwizard-api-dolt-dog

## Description
A POC for dropwizard api using hibernate to connect to dolt.

## Tech stack
- java
- maven
  - dropwizard
  - hibernate
  - mysql drivers

## Docker stack
- maven:3-openjdk-17
- dolthub/dolt-sql-server

## To run
`sudo ./install.sh -u`
[Endpoint](http://localhost/dogs)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Unoffical tutorial](https://nulpointerexception.com/2018/07/12/dropwizard-apis-to-read-write-from-database-using-hibernate/)
