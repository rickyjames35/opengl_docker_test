# opengl_docker_test
Simple docker image for running an OpenGL application in a docker container.

To run this example `cd` into the repo and run the following command:
```
xhost +local:docker && \
docker compose up --build
```

After that you should see `glxgears` popup along with info about the GPU printed to console.