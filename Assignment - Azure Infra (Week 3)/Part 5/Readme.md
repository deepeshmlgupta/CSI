1. Create a file of index.html
2. Create a Dockerfile for this folder
3. Build the docker image
   ```bash
   docker build -t myap
   ```
- ![image](https://github.com/deepeshmlgupta/CSI/assets/108192513/e822dcb0-78b3-4e00-97e6-a29288f9d1ee)

4. Docker Container
   ```bash
   docker run -d -p 8080:80 myapp
   ```
    ```bash
   docker ps
   ```
- ![Screenshot 2024-06-08 232114](https://github.com/deepeshmlgupta/CSI/assets/108192513/e1186213-ec18-4dc2-9271-8361fc857427)
