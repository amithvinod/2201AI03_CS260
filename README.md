# DBMS_LAB_CS260_2024 - 2201AI03
DBMS_LAB_CS260_2024
ROLL NUMBER : 2201AI03

PROJECT ROOT FOLDER : proj1/project1

ER DIAGRAM in proj1 directory

for installing and running project(with docker):
## Prerequisites

Before proceeding, ensure you have the following tools installed on your system:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

## Setup
1. Clone this repository to your local machine. 
2. Navigate to the root directory of the cloned repository.
3. Ensure that .env file is present in the root.
4. Run the program with the following command
```
	docker compose up --build
```
5. Run the application in the browser following [http://localhost:8000](http://localhost:8000)



For installing and running project(without docker):
Make sure you have node and npm installed before hand.

1) Clone the proj1 directory to your machine.
2) Edit the index.mjs line 46,47 change the username and password of MySQL to your local MySQL instance.
3) create the database locally and name it "DBMS_project"
4) In the porj1 directory run the following commands
   ```
   npm install
   node index.mjs
   ```
5) Run the application in the browser following [http://localhost:8000](http://localhost:8000)
