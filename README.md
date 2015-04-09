# nodejs-less

This Dockerfile extends `node:latest` and adds less, and plugins for that which are required for some builds. It is intended to be used for building the assets in your project.

The workdir is set to `/app`.

# Example uses

```
docker run --rm -v `pwd`:/app evolution7/nodejs-less styles.less > styles.css
```

