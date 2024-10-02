Assuming Dockerfile, docker-compose.yml, and other necessary files are in the repository.

1. Run this script to create a new user of docker on the server. 

```bash
sudo apt update
sudo apt install -y docker.io
sudo usermod -aG docker $USER
```
2. Login to private Dockeer Repository

```bash
docker login -u yourusername -p yourpassword
```
3. Place `docker.yaml` in `.github/workflows/` directory

## Important

Dont Forget to add `AWS_HOST`, `AWS_USER`, `AWS_SSH_KEY`, `DOCKERHUB_USERNAME`, and `DOCKERHUB_TOKEN` in your github repository secrets.