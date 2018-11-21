

    docker run --rm -p 8800:8888 \
        -e JUPYTER_ENABLE_LAB=yes \
        -e GRANT_SUDO="yes" \
        -e PASSWORD="nuiet" \
        -v "$PWD":/home/jovyan/work \
        jupyter/scipy-notebook