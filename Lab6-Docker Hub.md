## Common Docker Hub Commands

Search for Images
```
docker search ubuntu
```

Pull an Image from Docker Hub
```
docker pull ubuntu
```

List Local Images
```
docker images
```


Log in to Docker Hub before pushing images to Docker Hub. You will be prompted for your Docker Hub username and password
```
docker login
```

Rename an Image
```
docker image tag <orginal-image-name>:tag <dockerhub-username/final-image-name>:tag
```
Push the Image:
```
docker push meharcloudthat/<image-name>:<tag>
```

