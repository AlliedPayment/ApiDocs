# ApiDocs

[This static site](https://docs.alliedpayment.com) is being hosted via GitHub pages

## Development


### Prerequisits
- GIT
- An http static file server or NodeJS available on the box.
  - If using node to host the site for development run `npm install` to install the [static-server](https://www.npmjs.com/package/static-server) package
  - Run `npm start` to start the static-server package.
    - By default this will consume port `9080`.
    - If you need to attach to a different port run you can run the static-server directly and pass it a port `static-server -p 7777`
      - Note: you may need to install the `static-server` package globally (`npm i -g static-server`) to call it directly from the terminal.
