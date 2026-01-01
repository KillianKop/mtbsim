# mtbsim
A mountain biking simulator using Chrono

## Building Chrono
Please follow the instruction to create an image from Chrono project: https://api.projectchrono.org/docker_installation.html
For this project we need only core(default) and vehicule module

## (optional) build a simple application

``` docker compose -f contrib/docker/docker-compose.yml up -d vnc
docker ps ```

```docker compose -f contrib/docker/docker-compose.yml run --rm dev ```

``` echo $DISPLAY ```

``` cd ~/chrono-dev/template_project/build
./my_demo ```






## Building Dockerfile.chrono

docker build -f Dockerfile.chrono -t chrono-vehicle .
appr 1270s

