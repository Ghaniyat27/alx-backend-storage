# NoSQL MongoDB Project

This project contains scripts and Python programs to interact with MongoDB.

## Requirements

- Ubuntu 18.04 LTS
- MongoDB 4.2
- Python 3.7
- PyMongo 3.10

## Setup

### Install MongoDB

```sh
wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add -
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.2.list
sudo apt-get update
sudo apt-get install -y mongodb-org
sudo service mongod start
