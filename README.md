# ApiDocs

This static site is being hosted in an S3 bucket named `allied-api-docs`.

## Prerequisits

- GIT
- An http static file server or NodeJS available on the box.

## Development

- If using node to host the site for development run `npm install` to install the [static-server](https://www.npmjs.com/package/static-server) package
- Run `npm start` to start the static-server package.
  - By default this will consume port `9080`.
  - If you need to attach to a different port run you can run the static-server directly and pass it a port `static-server -p 7777`
    - Note: you may need to install the `static-server` package globally (`npm i -g static-server`) to call it directly from the terminal.

### Deployment

**The live site is not generated directly from this repositories source. The static assets are manually deployed to the S3 bucket.**

- Navigate to the S3 bucket https://s3.console.aws.amazon.com/s3/buckets/allied-api-docs/
- Upload files as needed to deploy changes.

**Note: All of the files in this S3 bucket should have public read permissions**

The live site lives here:
[https://s3.amazonaws.com/allied-api-docs/index.html](https://s3.amazonaws.com/allied-api-docs/index.html)
