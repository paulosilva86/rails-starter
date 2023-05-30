# Getting Started

### Prerequisites
1. Install Docker Desktop: https://www.docker.com/get-started/
2. Create a new repository from this template.
<img width="212" alt="Screenshot 2023-05-30 at 15 14 21" src="https://github.com/paulosilva86/rails-starter/assets/1209182/6c61a1d2-cce0-4377-abc5-69e3556dddda">


### Installation
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

<img width="749" alt="Screenshot 2023-05-30 at 15 30 13" src="https://github.com/paulosilva86/rails-starter/assets/1209182/f0d9256f-6f10-46d4-bfc6-b1beadf0cb0e">


