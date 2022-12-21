
### Topics to be covered;

- Tools needed to develop applications for cloud platforms
- APIs
- Building a Node.js server that receives requests and sends responses
- Git
- Package management for dependencies

### Getting started

### Installing Node and NPM 
NPM is used to manage software dependencies.
Use this [link](https://nodejs.org/en/download/) to install Node which includes NPM.

### Installing Ionic CLI

The Iconic CLI is requires to serve and build the frontend. Follow the instructions to download Iconic CLI [here](https://ionicframework.com/docs/installation/cli).

### Installing Python3

Python is a powerful programming language. Download and install python for your OS [here](https://www.python.org/downloads/)

### Amazon Web Services
  
#### Account Setup

We'll use AWS to provision cloud resources
Use this [link](https://portal.aws.amazon.com/billing/signup#/) to create a new account

### AWS CLI 

AWS CLI is used to interface with AWS. Download the CLI for your OS using [https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)

### Useful tools 

#### Postbird

**[Postbird](https://github.com/paxa/postbird)**

It is useful GUI to interact with our provisioned Postgres database.

#### Postman

**[Postman](https://www.getpostman.com/downloads/)**

Postman is a useful tool to issue and save requests.
Used to create GET,POST, PUT  requests and to automatically test endpoints.

### Designing an API

### What is a Server
A computer connected to a network.

**Cloud server** - a computer connected to a network that is managed by someone else.

### How to build a server?

We use NodeJS to build servers - A Javascript  based server-side environment to build applications.

Express - a web application server framework

### Application Program Interface

Used to control servers

#### RESTful APIs

RESTful APIs use requests, paths, types and bodies to perform a specific action.

#### Consumable APIs

Consumable APIs are APIs that are accessible to those outside the organisation. 

### Standing Up a Cloud Capable Server

#### Node 

**Node** is a powerful framework for building network applications outside the browser using Javascript.
Node is used alongside Express to handle http requests and responses.

#### Typescript

**Typescript** is a flavor of Javascript that forces hard typing on variables and methods.
This prevents implementation errors like passing a string instead of a number.
It compiles as pure Javascript.

### Testing

#### Unit testing

Unit test ensure tat our atomic functions and methods perform their tasks correctly. **[Mocha and Chai](https://mochajs.org/)** is used for thia purpose.

### Running Mocha and Chai Tests

```npm test``` is used to ru all files that match the pattern ```.tests.ts``` and is defined in the ```package.json``` file.

### Integration Tests

Integration Tests ensure every endpoint in our software package perform theirs tasks correctly., fails appropriately, and communicates with other systems in a predictable manner.

**[Postman](https://www.getpostman.com/)** is used as an integration testing framework.

### Git for Cloud Development

- Best practice is to no push all changes to master branch, only code that has been reviewed and ascertained to work should be pushed to the master or main branch.

### Packages

**Packages** are libraries of code that are written by other developers and made available through open-source licenses.

Packages help us to develop quickly.

