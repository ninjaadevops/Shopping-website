# Shopping Cart  
A simple E-commerce website using Flask.

## Steps to deploy on Docker ##
**Steps**
1. Launch an EC2 instance on Aws
2. Update all the packages
3. Clone the code
4. Install Docker in the machine
5. Build the docker image
6. Run the docker container

## Commands to Deploy on Docker ##

```
Sudo apt update
```
```
Sudo apt upgrade
```
```
Git clone https://github.com/ninjaadevops/shopping-website.git
```
```
ls
```
```
cd shopping-wensite
```
```
sudo apt-get install docker.io -y
```
```
docker --version
```
```
sudo docker build -t shopping-website .
```
```
sudo docker run -p 8080:8080 <imageId>
```
```
sudo docker ps
```

## Dependencies ##
1. Python3
2. Flask
3. Sqlite

## How to run in a local environment ##
1. Set up database by running database.py (Or you can reuse existing database included in the repo)
2. Run main.py
3. Enter localhost:5000 in the browser

## Pipenv instructions ##
1. Install pipenv (python3 -m pip install --user pipenv)
2. Install dependencies (pipenv install --dev)
3. Setup database (pipenv run python database.py)
4. Run the server (pipenv run python main.py)
5. Enter localhost:5000 in the browser

## Sample User ##
Sample credentials present in existing database:
Username - sample@example.com
Password - sample

