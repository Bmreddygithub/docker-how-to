# python-docker

A simple Python app for [Docker's Python Language Guide](https://docs.docker.com/language/python).
CLone the docker
git clone https://github.com/docker/python-docker
move venv to .venv
>python3 -m venv .venv  
Install pop requirements 
>python3 -m pip install -r requirements.txt
Run false 
>python3 -m flask run
init docker
> docker init
start docker project 
>docker build --tag python-docker .

Show all the docker images
>maheshreddybavanam@Maheshs-MacBook-Air python-docker % docker images
REPOSITORY      TAG       IMAGE ID       CREATED         SIZE
python-docker   latest    21c9ae915366   3 minutes ago   123MB

Create a docker tag 
>docker tag python-docker:latest python-docker:v1.0.0

Remove Image

>docker rmi python-docker:v1.0.0

Run the docker contaner 
>docker run python-docker

build and run the project
>docker compose up --build
