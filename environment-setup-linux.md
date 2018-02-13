# Environment Setup For Ubuntu Linux

The guide is written to help you setup the development tools that you will need for your project, it is written sequentially so please stick to the order of it, do not skip steps and you shall not face any problems.

All commands written in instructions are commands to be written in the Linux terminal.

---

![alt text](https://nodejs.org/static/images/logos/nodejs-new-pantone-black.png "Node.js")

## Installation:


Add the official stable repository

```
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
```

Install via package manager

```
sudo apt-get install -y nodejs
```

Install build tools

```
sudo apt-get install -y build-essential
```

## Usage:

Execute a Javascript file

```
node example.js
```

---

![alt text](https://webassets.mongodb.com/_com_assets/cms/mongodb-logo-rgb-j6w271g1xn.jpg "mongoDB")

## Installation:


Import the public key used by the package manager.

```
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2930ADAE8CAF5059EE73BB4B58712A2291FA4AD5
```

Create a list file for mongoDB

```
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.6 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.6.list
```

Reload local package database.


```
sudo apt-get update
```

Install the latest stable version of mongoDB

```
sudo apt-get install -y mongodb-org
```

## Usage:

Start mongod service

```
sudo service mongod start
```

Open another seperate terminal window and start the mongod process listener and keep it open

```
mongod
```

In the other terminal window begin using the mongoDB shell

```
mongo
```

---

![alt text](https://cdn.worldvectorlogo.com/logos/angular-3.svg "Angular")

## Installation:


Install Angular CLI via npm(Node Package Manager, already installed with Node.js).

```
npm install -g @angular/cli
```

## Usage:


[Check the official CLI documentation.](https://github.com/angular/angular-cli/wiki)

---

Vue.js & Express.js do not need installation, they are automatically installed in the project dependencies.

Goodluck people :metal: