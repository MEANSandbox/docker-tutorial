# docker-tutorial
a collection of basic tutorial dedication for windows developer(who are new to docker and linux)

docker tutorial to create ubuntu container and set it up for production level(for MEAN stack)
how to restart already created docker ?(with docker run ubuntu command )


docker run -it ubuntu
i for interactive (it keeps STDIN open even if not attached(what is not attached ?))
stdin/stdout are the input and output stream of the process
t for allocating pseudo-TTY(a pseudo terminal also known as tty or pts connects a user's terminal 
to the stdio and stdout ) 

docker run -d p 80:80 --name webserver nginx

docker stop webserver
docker start webserver

docker rm -f webserver(stop & remove container but not the nginx image)

docker rmi nixnx(to remove the image(pass imageID or name))
 
 show all container #docker ps -a
 show running container #docker ps
 
 


