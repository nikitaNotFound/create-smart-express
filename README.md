# create-smart-express
CLI tool for express project initialization with TS, auto-swagger, dotenv, rebuild-on-change scripts and more.

## Package list
- typescript and tslint
- swagger-ui-express with swagger-autogen
- dotenv
- express-async-handler
- cors
- nodemon

## Feature list
- npm start runs script with rebuild-on-change that helps you to automatically update refresh your app on every change.
- Automatic swagger documentation available in /swagger endpoint using swagger-autogen (read documentation to learn how to document your API)
- Error handler middleware that wraps all exceptions in one format response
- Environment variables support with dotenv package
- Async controller handlers
- Lite tsling and tsconfig settings

> Command creates regular files, that can be changed and configured as you want
