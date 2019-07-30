# docker-jupyter

Para crear un docker con jupyter la forma mas sencilla es:

```bash
docker run -it --rm -p 8888:8888 -p 4040:4040 -v c:/App/Workspace:/home/jovyan/workspace jupyter/tensorflow-notebook
```
