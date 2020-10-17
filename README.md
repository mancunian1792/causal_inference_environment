# causal_inference_environment
Containerized causal discovery and inference packages within one easy to use environment.

# Get Docker
[Install Docker](https://docs.docker.com/get-docker/) from here.

# Steps to run
The initial pull should take some time and space. (Nearly 3Gb, yikes.)
```
git clone git@github.com:mancunian1792/causal_inference_environment.git
cd causal_inference_environment
```
You can add all the other dependencies/packages you want in the requirements.txt before you start the script.
```
./start.sh
```

This will start a jupyter notebook with the current directory mounted.

```
docker ps -a
# This will show the port in which the container is running. Mostly, it will start from 32768 port.
```
Visit localhost:<port_you_see_in_docker_ps> to see the familiar jupyter notebook console with all the causal discovery and (SOON) causal inference packages.

# Feedback
Please raise an issue or email at ramani.h@northeastern.edu for any feedback or concerns.
