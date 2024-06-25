# learn-jupyter-notebooks
TODO: Learn Jupyter Notebooks

Resource: https://medium.com/codex/how-to-set-up-and-run-python-data-science-development-environment-with-jupyter-on-docker-17e04e11d6c

```
docker run -p 8888:8888 --name notebook -v .:/home/jovyan/work -e JUPYTER_ENABLE_LAB=yes --env-file .env -it jupyter/scipy-notebook:70178b8e48d7
```
`--env-file .env`はオプショナル
