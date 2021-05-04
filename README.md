# Web Worker POC

Please run below command to start web server which serves web worker:
```
$ yarn run web-worker
```
Now please visit [http://localhost:3001](http://localhost:3001) to test it.

Please run below command to start a web server which requests worker script from different origin:
```
$ yarn start
```

Below URL will demonstrate cross-origin Web Worker:

[http://localhost:3000/?workerUrl=http://localhost:3001](http://localhost:3000/?workerUrl=http://localhost:3001)
