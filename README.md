# Realtime

## Installation
```
$ yarn install
```
This will install all dependencies and build the application for production.


## Development
Run development server:
```
$ yarn start
```

Run ESlint:
```
$ yarn lint
```

Mock API (src/mock):
Install json-server
```
npm install -g json-server
```

Run:
```
json-server --watch db.json
```

## Production
Build the application by running:
```
$ yarn build
```
This will bundle the javascript to the `dist/` directory. You may then run the built server with:
```
$ yarn start-production
```
