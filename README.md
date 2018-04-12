# node-krb5-gm

[![Build Status](https://travis-ci.org/lgaticaq/node-krb5-gm.svg?branch=master)](https://travis-ci.org/lgaticaq/node-krb5-gm)

[![dockeri.co](http://dockeri.co/image/lgatica/node-krb5-gm)](https://hub.docker.com/r/lgatica/node-krb5-gm/)

> Docker Image for node apps with alpine linux, native dependencies and graphicsmagick

Supported tags and respective Dockerfile links

- 9.11.1, 9.11, 9, latest ([9.11/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/9.11.1/Dockerfile))
- 9.11.1-onbuild, 9.11-onbuild, 9-onbuild, onbuild ([9.11/onbuild/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/9.11.1/onbuild/Dockerfile))
- 8.11.1, 8.11, 8 ([8.11/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/8.11.1/Dockerfile))
- 8.11.1-onbuild, 8.11-onbuild, 8-onbuild ([8.11/onbuild/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/8.11.1/onbuild/Dockerfile))
- 6.14.1, 6.14, 6 ([6.14/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/6.14.1/Dockerfile))
- 6.14.1-onbuild, 6.14-onbuild, 6-onbuild ([6.14/onbuild/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/6.14.1/onbuild/Dockerfile))
- 4.9.1, 4.9, 4 ([4.9/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/4.9.1/Dockerfile))
- 4.9.1-onbuild, 4.9-onbuild, 4-onbuild ([4.9/onbuild/Dockerfile](https://github.com/lgaticaq/node-krb5-gm/blob/master/4.9.1/onbuild/Dockerfile))

## Create a Dockerfile in your Node.js app project
```dockerfile
FROM lgatica/node-krb5-gm:onbuild
# replace this with your application's default port
EXPOSE 3000
```

You can then build and run the Docker image:

```bash
docker build -t my-nodejs-app .
docker run -it --rm --name my-running-app my-nodejs-app
```

### Notes
The image assumes that your application has a file named package.json listing its dependencies and defining its start script.
