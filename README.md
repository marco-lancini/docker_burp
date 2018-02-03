# Burp Pro as a Docker Container

Full description can be found online: https://www.marcolancini.it/2018/blog-docker-burp/


## Usage

1. Place the Burp Professional JAR file and the licence key in the `_data/sources` folder
2. Export local IP address: `export LOCAL_IP=$(ifconfig en0 | grep inet | awk '$1=="inet" {print $2}')`
3. Start services: `docker-compose up`
