```
docker build -t py-app-1 -f Dockerfile .
```

```
docker run -p 8080:8000 py-app-1
```

```
docker ps
``` 

```
docker run -it py-app-1 /bin/bash
```