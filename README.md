docker build --rm -f Dockerfile -t ubuntu:robert .
docker run --rm -it ubuntu:robert
docker container ls --all
docker run --rm -it -v `pwd`:/developer ubuntu:robert
docker image ps
docker commit blissful_booth ubuntu:robert-dotbare
