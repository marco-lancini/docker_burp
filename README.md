# Burp Pro as a Docker Container

How to run any GUI application (and Burp Pro in particular) from Docker

A full description can be found on my website: https://www.marcolancini.it/2018/blog-docker-burp/

![Burp in Docker](https://www.marcolancini.it/images/posts/blog_docker_burp_3.jpg)


## Usage

1. Place the Burp Professional JAR file and the licence key in the `_data/sources` folder
2. Export local IP address: `export LOCAL_IP=$(ifconfig en0 | grep inet | awk '$1=="inet" {print $2}')`
3. Start services: `docker-compose up`
