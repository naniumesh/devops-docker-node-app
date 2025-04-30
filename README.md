# DevOps CI/CD Demo Project

## How to Run

### 1. Install dependencies
npm install

### 2. Build Docker image
docker build -t my-web-app .

### 3. Run Docker container
docker run -p 3000:3000 my-web-app

Open http://localhost:3000