# Installation

<p class="description">Install</p>

## npm

To install and save in your `package.json` dependencies, run:

```sh
// with npm
npm install

// with yarn
yarn install
```

Please note that [react](https://www.npmjs.com/package/react) >= 16.8.0 and [react-dom](https://www.npmjs.com/package/react-dom) >= 16.8.0 are peer dependencies.

## Quick start

Get up and running on the client-side.

```sh
// with Docker
docker build -f Dockerfile.dev .

// Copy the id from the line "Successfully built CONTAINER_ID"

docker run -it -p 3000:3000 CONTAINER_ID
```
