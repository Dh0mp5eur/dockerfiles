FROM golang:1.6

RUN go get github.com/abesto/docker-compose-graphviz

RUN apt-get update && apt-get install -y graphviz

CMD cd /mnt && docker-compose-graphviz | dot -odocker-compose.jpg -Tjpg
