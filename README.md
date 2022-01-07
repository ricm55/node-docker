### Node app with docker

Just some tests of best practices for using docker with node.

This app is an api of everything. You can POST and GET data to any endpoint you like.

exemple:
```bash
curl --request POST --url http://localhost:8000/notes --header 'content-type: application/json' --data '{"msg":"testing 1", "msg":"testing 2","msg":"testing 3"}'

```
```bash
 curl --request GET --url http://localhost:8000/notes
```

All credits go to the official documentation of docker where I follow the tutorial: https://docs.docker.com/language/nodejs/