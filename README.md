# Quick tutorial using this video guide: https://www.youtube.com/watch?v=np_vyd7QlXk

docker run -it {Name of the image} # runs the container using an image
docker ps # displays all containers running in PC
docker ps -a # displays all containers in PC
docker run -d {Name of the image} # runs the container on background
docker run -p {PC port}:{container port} {Name of the image}
docker run --name{Name to give the container}
docker start {Name of the container} # starts an already created container