# Create ACR and pull image from ACR and Create a container from it

1. Docker Image download
   ```bash
   docker pull ngnix
   ```

2. To Show Images
   ```bash
   Docker images
   ```

3. Docker Image
   ```bash
   docker tag 4f67c83422ec deepeshacr.azurecr.io/ngnix
   ```

4. To Show Images
   ```bash
   Docker images
   ```

5. Add a Remote Repository:
   ```bash
    docker login deepeshacr.azurecr.io
     username:
     password: 
   ```

6. Docker Push
   ```bash
   docker push deepeshacr.azurecr.io/nginx
   ```
