
## Installing Docker on Linux
```
https://docs.docker.com/install/linux/docker-ce/ubuntu/#set-up-the-repository
```

After completing the installation steps, test out Docker:

```
sudo docker run hello-world
```

This should download and run the hello-world container from docker hub and printing "hello world" to your console

### Installing Docker Compose
We must manually install Docker Compose on linux. see the insruction below link (Click on the tab for Linux)

```
https://docs.docker.com/compose/install/#install-compose
```



```
docker run -p 5000:3000 -v $(pwd):/app <imagid>
```

