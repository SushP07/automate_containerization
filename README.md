# This project Automates the containerization of WebApp

## Clone the repository
```bash
git clone https://github.com/your-username/docker-gha.git
cd docker-gha
```

### Create a virtual environment
```bash
python -m venv venv

### Activate the virtual environment
#### On Windows:
.\venv\Scripts\activate
#### On macOS/Linux:
source venv/bin/activate

##### Install requirements
pip install -r requirements.txt

```

## Using Docker
You can run the application directly using the pre-built Docker image. Pull the image from the registry and run it on your local machine:

### Pull the Docker image
```bash
docker pull ghcr.io/your-username/docker-gha:latest

### Run the container
### Maps the container port to your local port 8080
docker run -p 8080:8080 ghcr.io/your-username/docker-gha:latest

```
