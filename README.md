# Node, TypeScript and Express Starter Template

Simple started template to get something up and running with Node, TypeScript and Express.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Built with Node 12.14.1 and npm 1.13.6

### Installing

A step by step series of examples that tell you how to get a development env running

Clone onto your workstation with your project name (here my-new-project)

```
git clone https://github.com/jyoung/node-ts-express-starter.git my-new-project
```

In the root folder (my-new-project) create a .env file to hold environment variables.
add the following to the .env file

```
#set to production when deploying to production
NODE_ENV=development

#nodejs server config
SERVER_PORT=4040
```

Run the command `npm install` to install all the dependencies

```
npm install
```

Run the command `npm run dev` to start the server

```
npm run dev
```

## Acknowledgments

This starter was built from the tutorial by David Neal at https://developer.okta.com/blog/2018/11/15/node-express-typescript.
Huge thanks to him for putting it together.
