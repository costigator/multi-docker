# create app
npx create-react-app client

# build client/server/worker docker
cd FOLDER
docker build -f Dockerfile.dev .
docker run CONTAINER_ID

# build the project
docker-compose up --build
