# goit-typescript-hw-01

------- Installation and configuration of the development environment

$ node - v  // v18.16.0

$ tsc -v // Version 5.2.2 // if (!true) $ npm install -g typescript

------- Compiler settings - Created a new tsconfig.json

$ tsc --init

= Edit = tsconfig.json
------- Create files ------
 index.html
  src/index.ts
  src/concatenation.ts
---

$ tsc

$ tsc -w
------- Create server = @web/dev-server
$ npm init -y // package.json
$ npm i --save-dev @web/dev-server

 in  package.json add line - "start": "web-dev-server --node-resolve --open --watch"

$ npm start
