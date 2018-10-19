### Install
yarn install

### Run
`npm run server` to run the config server (http://localhost:3000 to view the config)
`node index.js` to run the demo (accessing http://localhost:3001 will clear the cache)


### TODO
- Use Launch Darkly's REST APIs instead of their SDK
- Fix stampede issue in Cache manager, so that the cache is built before attempting to handle more requests to build the tree
