## Getting started
* `npm i`
* include "mocha": "^4.0.1" globally if not yet done by npm install -g mocha

## Todo

create a basic server with express
that will send back the index.html file on a GET request to '/'
it should then send back jsonData on a GET to /data

## Fetch all branches locally

```
git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
git fetch --all
git pull --all
```
