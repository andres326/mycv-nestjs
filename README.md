## Description

This is an API built with NestJs that allows to upload a car to be sold and make an estimate on how much it should cost. The car would be estimated until it would be approved for and admin user. It has a complete user module to register, authenticate and edit a user, all this with the purpose of having a strong auth module on the application. It uses sqlite as a db just for test purposes, there is a module called ``ormconfig.js`` where the providers can be configured.

This was created as a project to study NestJS, following all the documentation and adding unit tests.

## Installation 
You'll need NodeJs to be installed on your machine. Clone the repository and install the dependencies using:  

```bash
npm install
```

After the installation, you can start running

```bash
npm run start:dev
```

## License

[MIT](https://choosealicense.com/licenses/mit/)