 **Installation**
 ``` bash
    mkdir scratch
    cd scratch
    npm init -y
	npm install @nestjs/common@7.6.17 @nestjs/core@7.6.17 @nestjs/platform-express@7.6.17 reflect-metadata@0.1.13 typescript@4.3.2
```

**package.json**

 - **@nestjs/common** - Contains vast majority of functions, classes ,etc, that we need from Nest
 - **@nestjs/platform-express** - Lets Nest use Express JS for handling HTTP requests
 - **reflect-metadata** - Helps make decorators work.
 - **typescript** - We write Nest apps with Typescript.

**Request and Response Cycle with Nest tools**

> *Request => Server => Response*

- Validate data contained in the request [**Pipe**]
- Make sure the user is authenticated [**Gaurd**]
- Route the request to a particular function [**Controller**]
- Run some business logic [**Service**]
- Access a database [**Repository**]


**Parts of Nest**
- **Controllers** => Handles incoming requests 
- **Services** => Handles data access and business logic
- **Modules** => Groups together code
- **Pipes** => Validates incoming data
- **Filters** => Handles errors that occur during request handling
- **Gaurds** => Handles authentication
- **Interceptors** => Adds extra logic to incoming requests or outgoing responses
- **Repositories** => Handles data stored in a DB

**RUN**
- `npx ts-node-dev src/main.ts`
 
