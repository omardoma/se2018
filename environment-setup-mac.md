# Environment Setup For Mac

The guide is written to help you setup the development tools that you will need for your project, it is written sequentially so please stick to the order of it, do not skip steps and you shall not face any problems.

All commands written in instructions are commands to be written in the terminal and uses Homebrew for installation.

---

![alt text](https://img.wonderhowto.com/img/09/53/63613273648659/0/mac-for-hackers-set-up-homebrew-install-update-open-source-tools.1280x600.jpg "Homebrew")


## Install Homebrew:

This step can take some time, so don't worry, just leave it to finish

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Update Homebrew’s package database

```
brew update
```

---

![alt text](https://nodejs.org/static/images/logos/nodejs-new-pantone-black.png "Node.js")

## Installation:

Install via Homebrew

```
brew install node
```

## Usage:

Execute a Javascript file

```
node example.js
```

---

![alt text](https://webassets.mongodb.com/_com_assets/cms/mongodb-logo-rgb-j6w271g1xn.jpg "mongoDB")

## Installation:


Install the latest stable version of mongoDB

```
brew install mongodb
```

Create mongoDB data directory

```
mkdir -p /data/db
```

## Usage:

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

BI students skip this step  
Install Angular CLI via npm(Node Package Manager, already installed with Node.js).

```
npm install -g @angular/cli
```

## Usage:


[Check the official CLI documentation.](https://github.com/angular/angular-cli/wiki)

---

![alt text](https://ih0.redbubble.net/image.324410142.0465/flat,800x800,075,f.u4.jpg)

## Installation:


Engineering students skip this step  
Install Vue.js CLI via npm(Node Package Manager, already installed with Node.js).

```
npm install --global vue-cli
```

## Usage:


[Check the official CLI documentation.](https://vuejs.org/v2/guide/installation.html)

---

Express.js do not need installation, they are automatically installed in the project dependencies.

Goodluck people :metal:
