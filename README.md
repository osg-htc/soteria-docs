
You can run the docs locally by running the following line in the root directory.

### amd64
```console
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

### arm
```shell
docker run --rm -it -p 8039:8000 -v  ${PWD}:/docs ghcr.io/afritzler/mkdocs-material
```

https://localhost:8039