# ApiDocs

[This static site](https://docs.alliedpayment.com) is being hosted via GitHub pages

## Development (Running Locally)

### Prerequisits
- GIT
- [NodeJS](https://nodejs.org)
  - or any other http static file server

#### Usage

- Clone the repo
  - `git clone https://github.com/AlliedPayment/ApiDocs`
- Navigate into the project directory
  - `cd ApiDocs`
- Install dependencies ([static-server](https://www.npmjs.com/package/static-server))
  - `npm install` or `npm i` 
- Start the static server
  - `npm start`
- Open browser to locally hosted docs site
  - `http://localhost:9080`
  
##### Custom Port for static-server

- Install static server globally.
  - `npm i -g static-server`
- Navigate to project directory
  - `cd ApiDocs`
- Start static server with specified port.
  - `static-server -p PORT_NUMBER_HERE`
 
For more information regarding static-server options please refer the docs: [Go To static-server docs](https://www.npmjs.com/package/static-server)
