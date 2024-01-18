# Template Backend Application
This is a template repo for creating new Express server applications.

## Setup

### Prerequisite Downloads
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/en)
- [VSCode](https://code.visualstudio.com/)

### Installing

```bash
git clone repo-link
cd repo-name
npm install
```

### Executing

- Start dev server: `npm run dev`
- Compile: `npm run build`
- Start build: `npm start`
- Format all src files: `npm run format`

### VSCode Extensions

- **JavaScript and TypeScript Nightly**
- **Prettier**
  - Usage: press `Shift + Alt + F` to format your file
  - If prompted, select Prettier as the default formatter
- **REST Client**
  - Usage: create a `.rest` file to send http requests
- **TODO Highlight**\*
- **vscode-icons**\*

_\* optional, but useful_

## Documentation

### File Structure

- `/dist`: compiled build, not tracked by repo
- `/node_modules`: node dependencies, not tracked by repo
- `/rest`: .rest files for VSCode REST Client
- `/src`
  - `/config`: configuration files, like database config
  - `/controllers`: controller classes for handling requests & responses
  - `/middlewares`: middleware functions and utilities
  - `/models`: data models for interacting with database, contains TypeScript interfaces for db objects, typeguards, etc.
  - `/routes`: routing files which pass requests to controllers
  - `/services`: business logic for controllers to call
  - `/types`: custom types besides those used in data models
  - `/utils`: general utilities

## Resources

### Express

- [Official Guide](https://expressjs.com/en/guide/routing.html)
- [Full Stack Open Part 3: Express](https://fullstackopen.com/en/part3)

### TypeScript

- [Official Documentation + Learning](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [Official Cheat Sheets](https://www.typescriptlang.org/cheatsheets)
- [Full Stack Open Part 9: TypeScript](https://fullstackopen.com/en/part9)

### Other Topics

- [Promises: Mozilla Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)
