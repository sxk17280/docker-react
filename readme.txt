docker run -p 3000:3000 -v /app/node_modules -v ${PWD}:/app saitejagoudkasala/frontend

docker build -f Dockerfile.dev . -t saitejagoudkasala/frontend

//add below line in the npm start script 

WATCHPACK_POLLING=true 