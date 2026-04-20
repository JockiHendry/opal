This project is forked from https://github.com/permitio/opal. I use it to build `opal-client-cedar` image based on the output of https://github.com/JockiHendry/cedar-agent.

### How To Use

To run OPAL client with Cedar agent that uses Cedar 4.9.1, run the following command:

```
docker run --rm -p 8180:8180 jockihendry/opal-client-cedar:0.9.4-patch1
```

Open http://localhost:8180/swagger-ui in a browser to verify that Cedar Agent is running and the version is `0.2.0-cedar4.9.1`.
