# Docker & Rails app

## Description
This instructions build Rails tasks app with docker-compose

## Version
Docker version 18.06.1-ce  
docker-compose version 1.23.2  
Rails ~> 5.2.3
ruby 2.6.3  
mysql 5.7  

## Getting started
1.git pull files  
```
$ git clone https://github.com/jbdzizou/taskapp.git  
$ cd taskapp
```
2.container build  
`$ docker-compose up -d`

3.Command to execute DB creation task in Rails container  
`$ docker-compose run web bundle exec rake db:create`

4.login to localhost(your chrome or etc)  
http://localhost:3000 or http://address:3000

## Usage
Click the Bottan and Registration your task  
you can check the task lists and edit and delete
