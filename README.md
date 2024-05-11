# DBMS_LAB_CS260_2024 - 2201AI03
DBMS_LAB_CS260_2024
ROLL NUMBER : 2201AI03

for installing and running project(with docker):

project root folder is proj1/project1

## Prerequisites

Before proceeding, ensure you have the following tools installed on your system:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

## Setup
1. Clone this repository to your local machine. 
2. Navigate to the root directory of the cloned repository.
3. Ensure that .env file is present in the root.
4. Run the program with the following command

'''
	docker compose up --build
 '''
5. Run the application in the browser following [http://localhost:8000](http://localhost:8000)



for installing and running project(without docker):
 make sure u have node and npm installed.
1) clone the proj1 directory to your machine
2) edit the index.mjs line 46,47 change the username and password of mysql to yours
3) create the database locally and name it "DBMS_project"
4) on the porj1 directory run the following commands
   npm install
   node index.mjs

5) Run the application in the browser following [http://localhost:8000](http://localhost:8000)
