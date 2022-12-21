
### Topics to cover

- Protecting secrets.
- Tools for deploying application code.
- How to deploy a server to a cloud environment.
- Code organization for larger applications that interact with multiple components.
- Connecting persistent storage to applications in a cloud environment.

### Object-Relational Maps (ORM)

- ORMs can handle connections to our database.

- Help manage database state 

- Convenient patterns to migrate databases.

- Migration refers to modifying the database

- Up migration is the process of modifying the database to a newer state.

- Down migration is the process of reversing an up migration, to a prior state.

An example of an ORM is **[Sequelize](http://docs.sequelizejs.com/)**

**Model** - It is a data representation of some group of data.

We use the ```@Table``` decorator and extend the base sequelize ```Model``` class to link our model to our database table.

**Parameters** - The model contains instance parameters.

 We use the ```@Column``` decorator to link our parameters to the table columns. 
 
The symbol ```!``` is used to specify whether a field in the table can be null.

Sequelize handles the datatype mappings from TypeScript types to Postgres column datatypes.

**Seeding** - Seeds are defaultrows of data that will be inserted upon database creation.

**Decorators**
Also known as annotations. The are feature of sequelize-typescript are used to link database features with our models


### Deploying Server to the Cloud

### Basic AWS architecture

### Example of a build process

- Transpile typescript
- include some source files
- zip an archive 
- upload to elastic beanstalk

### Using AWS Elastic Beanstalk

Elastic Beanstalk is a tool used  to deploy your code to AWS services and infrastructure with minimal effort.

### EB CLI

- EB CLI is a Command Line Interface

### Creating Deployable Build Archives and Deploying

- We must package our code into a format that is usable by Elastic BeansTALK

- This can be done by transpiling  our TypeScript intojavascript and then zipping the contants into a single file which can be uploaded.

