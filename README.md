# Getting Started

### Prerequisites
- Install Docker Desktop: https://www.docker.com/get-started/

### Installation
0. Create new repository from template.

1. Clone project from GitHub
```console
git clone git@github.com:<username>/<repository>.git
```

2. Move into project folder
```console
cd <repository>
```

3. Build Docker image
```console
docker-compose build
```

4. Create database
```console
docker-compose run web bin/rails db:create
```

5. Start the app
```console
docker-compose up
```

Open `http://localhost:3001` in a browser.
