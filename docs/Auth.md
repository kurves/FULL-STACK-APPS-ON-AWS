### Security Application

- Basic security and user aurhentication on the internet
- Concepts involved in password capture and storage including encryption
- Implementing secure communications between a client and server


### Basic Security and User Auth

- Password Storage 
- Passwords should not be stored in plain text
- Passwords should be encrypted in transit and storage
- Salted hashes are a good option

### Adding Authetication

## BCrypt 

Bycrpt is a package for hashing passwords

### Sessions, JWTs, and Environment Variables

#### JSON Web Tokens

#### Requiring Auth to Restrict Endpoint Usage

- authentication is used to validate the JWT is in the request authorization header.

### Building from source

use ``` npm run build ```

### Deploying to the Cloud 

- Once built, you can deploy changes to the elastic beanstalk instancing by running 

``` eb deploy```


### Examples of Good Security Policies

- npm - [npm](https://docs.npmjs.com/policies/security)

- AWS - [aws](https://aws.amazon.com/security/)
