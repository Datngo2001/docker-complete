## 1. Build images

```
docker build -t node-app-image ./node-app
```

```
docker build -t python-app-image ./python-app
```

## 2. Run container

```
docker run -d -p 3000:3000 --rm node-app-image
```

```
docker run -i -t --rm python-app-image
```
