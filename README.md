# docker-jupyter

El **objetivo** es crear un contenedor que haga uso de la capacidad de procesamiento de la GPU nvidia, tenga las principales librerias de Data Science en Python y permita usar el home del usuario que la levante.

Para eso tenemos que instalar el 

[Link 1](https://medium.com/@li.yuxiang.nj/configuring-tensorflow-on-arch-linux-using-docker-882cd2150ad8)
[Link 2](https://briancaffey.github.io/2017/11/19/tensorflow-gpu-setup-with-docker-on-arch-linux.html)


Para crear un docker con jupyter la forma mas sencilla es:

```bash
docker run -it --rm -p 8888:8888 -p 4040:4040 -v c:/App/Workspace:/home/jovyan/workspace jupyter/tensorflow-notebook
```
