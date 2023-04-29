#!/bin/sh
wsl_loc="//wsl.localhost/Ubuntu"
file_path="file:///$wsl_loc$(realpath $1)" && \
bash -c "\"$BROWSER\" $file_path"
