# Datacentric AI Competition
[https://https-deeplearning-ai.github.io/data-centric-comp/](https://https-deeplearning-ai.github.io/data-centric-comp/)

## Steps
* Setup Docker container
  `docker run --gpus all -d -it -p 8848:8888 -v $(pwd)/data:/home/jovyan/work -e GRANT_SUDO=yes -e JUPYTER_ENABLE_LAB=yes --user root cschranz/gpu-jupyter:v1.4_cuda-11.0_ubuntu-20.04_python-only`
* Curate data
* Run Initial Dataset
* Augment Dataset
* Repeat
