## Python Client

### Building with Docker

```bash
docker build -t $(basename $PWD | tr '[:upper:]' '[:lower:]') .
```

### Running with Docker

```bash
docker run --rm -it -v "$PWD/../../:/workspace" $(basename $PWD | tr '[:upper:]' '[:lower:]') /bin/bash
```
