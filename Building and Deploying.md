
### Topics to cover

- Protecting secrets.
- Tools for deploying application code.
- How to deploy a server to a cloud environment.
- Code organization for larger applications that interact with multiple components.
- Connecting persistent storage to applications in a cloud environment.

### Object-Relational Maps (ORM)

An example of an ORM is **[Sequelize](http://docs.sequelizejs.com/)**

**Model** - It is a data representation of some group of data.

We use the ```@Table``` decorator and extend the base sequelize ```Model``` class to link our model to our database table.

**Parameters** - The model contains instance parameters.

 We use the ```@Column``` decorator to link our parameters to the table columns. 
 
The symbol ```!``` is used to specify whether a field in the table can be null.

Sequelize handles the datatype mappings from TypeScript types to Postgres column datatypes.
