## Requirements for participation:

### Requirement 1: git and github must be installed

Git is a version control software that runs locally on your computer, where you can save snapshots of your code over time. If you need, you can then go back to older versions of your code.

Open the git website and download and install git by following the instructions on the website: https://git-scm.com/downloads

Check if git is successfully installed: git --version

Configure git:

```
git config --global user.name "Your name"
git config --global user.email "Your email"
Check configurations: git config --list
```

<br><br>

## Requirements for using docker container for test branch: new-basic-frontend

### Requirement 2: docker Engine ~~and docker-compose~~ must be installed

#### Run the docker container for a static website

<br>

Follow these instruction for ubuntu: https://docs.docker.com/engine/install/ubuntu/

Test if docker ~~and docker-compose~~ are successfully installed.

```
$ docker --version
```

<!--

```
$ docker-compose --version
``` -->

Have a look into the configuration file called <code>Dockerfile</code>. This configuration file is used to create a docker image.

```
FROM nginx
COPY . /usr/share/nginx/html
```

<br>

To create the image, execute the docker build command, like this:

```
$ sudo docker build -t "img-name" .
```

To start the image, execute the docker run command, like this:

```
$ sudo docker run -it -d -p 80:80 "img-name"
```

Enter <code>localhost</code> into your browser of choice.
Afterwards you can stop and start the image. If changes has been done its necessary to re-build the image.

```
$ sudo docker stop "CONTAINER ID"
```

List all containers, including "CONTAINER ID":

```
$ sudo docker ps
```
