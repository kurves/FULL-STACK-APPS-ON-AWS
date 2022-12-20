
### Domain Name System

- Used for routing

- AWS - Route 53 - provides the name server for the domain name
-  Route 53 allows one to set routing profile for the domain names and direct traffic to services in AWS.

### Deploying the frontend using AWS S3 and CloudFront

The static build artifacts  can be uploaded to an S3 bucket which can be linked to a CloudFront distribution. 

### Intro to Throughput and Concurrency

#### Scaling Up (Vertical Scaling)

- Scaling up involves improving the qualities of a particular i.e making he instance more powerful by increasing the ram , better CPU , fast GPU.

#### Scaling Out (Horizontal scaling)

- Scaling out involves adding more server instances.


### Automatic Bug Reporting

**[Sentry](https://sentry.io/)**  is used to catch errors and provide a stack trace to developers.

#### Testing Concurrency

- It is important to test how our cloud will react under high load.

**[Siege](https://www.joedog.org/siege-manual/)** is a lightweight CLI to create a large number of concurrent requests. (locally)

#### Monitoring 

- **[Cloudfare](https://www.cloudflare.com/)** is used for improved DNS with monitoring and failover capabilities.

- **[Datalog](https://www.datadoghq.com/product/)** for stack perfomance and health status.

- AWS - **[CloudWatch](https://aws.amazon.com/cloudwatch/)**

- Tools on cloud platforms can be used to monitor and trace your applications deployed on the cloud 
- Helps to identify  issues that may be leading to sub-optimal user experiences or broken code.



