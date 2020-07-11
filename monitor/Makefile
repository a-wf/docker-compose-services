
LOCAL_USER=$(shell id -u)

up: 
	LOCAL_USER=$(LOCAL_USER) docker-compose up  -d 

down: 
	LOCAL_USER=$(LOCAL_USER) docker-compose down 

up_debug: 
	LOCAL_USER=$(LOCAL_USER) docker-compose up 