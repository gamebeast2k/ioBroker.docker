## Using Information
Thats is a folk from https://github.com/ioBroker/ioBroker.docker
I do my best to  Maintenance this Repo.
The build instructions are tracked on [GitHub][this.project_github_url].
Automated builds are hosted on [Docker Hub][this.project_docker_hub_url].

#### Base docker image

    hart/alpine-node

#### Basic commands to run the container:

    docker run 
        --name iobroker 
        -p 8081:8081 
        -p 8082:8082 
        -p 8083:8083 
        -p 8084:8084  
        -v /<yourfolder>:/opt/iobroker
        -d -it gamebeast/iobroker

#### Image Size
    2018-06-26 = 391.7 MB
[this.project_docker_hub_url]: https://hub.docker.com/r/gamebeast/iobroker/
[this.project_github_url]: https://github.com/gamebeast2k/ioBroker.docker
