# Environment Setup For Windows

The guide is written to help you setup the development tools that you will need for your project, it is written sequentially so please stick to the order of it, do not skip steps and you shall not face any problems.

All commands written in instructions are commands to be written in the terminal installation.

---

![alt text](http://cmder.net/img/main.jpg "cmder")


## Install cmder:

Install via website. Go to website and download full version. Inside folder run "Cmder.exe".

[Cmder Download page](http://cmder.net/)

---

![alt text](https://nodejs.org/static/images/logos/nodejs-new-pantone-black.png "Node.js")

## Installation:

Install via website. Go to website and download current version.

[Node.js Download page](https://nodejs.org/en/)

## Installer:

Execute a node installer file and choose "npm package manager". 

```
node example.js
```

![alt text](http://blog.teamtreehouse.com/wp-content/uploads/2015/01/installer.png "node.js setup")

## Test:

Go to terminal "Cmder" and write following commands (each command separately). Each command should show you on terminal version of node & npm installed.

```
node -v
npm -v
```

![alt text](http://blog.teamtreehouse.com/wp-content/uploads/2015/01/verify.png "node.js setup")

---

![alt text](https://webassets.mongodb.com/_com_assets/cms/mongodb-logo-rgb-j6w271g1xn.jpg "mongoDB")

## Installation Basic setup:


Install via website. Go to website and download "community Server". 


[MongoDB Download page](https://www.mongodb.com/download-center?jmp=nav#community)


Create mongoDB data directory on "C" Disk (directory mongoDB was installed in).

```
1. Navigate to "C:\"
2. Create folder with exact name "data"
3. Navigate to "C:\data" (folder you created in previous step)
4. Create two folders: 
    4.1 Create folder with exact name "db"
    4.2 Create folder with exact name "log"
5. Navigate to "C:\Program Files\MongoDB\Server\3.6\bin" (MongoDB in installed on system)
6. Run "mongod.exe"
```

## Test:

Open another seperate terminal window and start the mongod process listener and keep it open

```
1. Navigate to "C:\Program Files\MongoDB\Server\3.6\bin" (MongoDB in installed on system)
2. Run "mongo.exe"
3. Write inside opened terminal:
    show dbs
```
## Installation setup from official MongoDB site:

Go to official website and follow guide:

[MongoDB Installation Guide](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)

---

**BI students skip Angular**

![alt text](https://cdn.worldvectorlogo.com/logos/angular-3.svg "Angular")

## Installation:

Install Angular CLI via npm (Node Package Manager, already installed with Node.js).
Go to terminal "Cmder" and write the following command:
```
npm install -g @angular/cli
```

## Usage:


[Check the official CLI documentation.](https://github.com/angular/angular-cli/wiki)

---

**Engineering students skip Vue.js**

![alt text](https://ih0.redbubble.net/image.324410142.0465/flat,800x800,075,f.u4.jpg)

## Installation:

Install Vue.js CLI via npm (Node Package Manager, already installed with Node.js).
Go to terminal "Cmder" and write the following command:
```
npm install --g vue-cli
```

## Usage:

[Check the official CLI documentation.](https://vuejs.org/v2/guide/installation.html)

---

Express.js does not need installation, it is automatically installed in the project dependencies.

Goodluck people :metal:
