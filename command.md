# Docker

* run
```console
docker run -it --gpus 1 -p 5000:5000 -p 1234:1234 -v $(pwd):/workspace pytorch/pytorch:1.9.0-cuda10.2-cudnn7-runtime /bin/bash
```


# install

```console
apt update;apt install git -y;
pip install GitPython
pip install mlflow
```
