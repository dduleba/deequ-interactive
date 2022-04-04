# Deequ interactive examples

## run with docker

```shell
$ docker run --name deequ-interactive -it -p 8888:8888 -v "${PWD}/notebooks":/home/jovyan/work  almondsh/almond:latest
Executing the command: jupyter notebook
[I 06:58:39.975 NotebookApp] Writing notebook server cookie secret to /home/jovyan/.local/share/jupyter/runtime/notebook_cookie_secret
[I 06:58:40.545 NotebookApp] JupyterLab extension loaded from /opt/conda/lib/python3.8/site-packages/jupyterlab
[I 06:58:40.545 NotebookApp] JupyterLab application directory is /opt/conda/share/jupyter/lab
[I 06:58:40.548 NotebookApp] Serving notebooks from local directory: /home/jovyan
[I 06:58:40.548 NotebookApp] Jupyter Notebook 6.1.4 is running at:
[I 06:58:40.548 NotebookApp] http://ff161096ee0d:8888/?token=9b6c3beaf4d1fd21b5987c78fad3bf7761712a0406c08089
[I 06:58:40.548 NotebookApp]  or http://127.0.0.1:8888/?token=9b6c3beaf4d1fd21b5987c78fad3bf7761712a0406c08089
[I 06:58:40.548 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 06:58:40.552 NotebookApp] 
    
    To access the notebook, open this file in a browser:
        file:///home/jovyan/.local/share/jupyter/runtime/nbserver-7-open.html
    Or copy and paste one of these URLs:
     or http://127.0.0.1:8888/?token=9b6c3beaf4d1fd21b5987c78fad3bf7761712a0406c08089
[I 06:58:43.577 NotebookApp] 302 GET /?token=9b6c3beaf4d1fd21b5987c78fad3bf7761712a0406c08089 (172.17.0.1) 0.78ms
```

[automatic suggestion of constraints](notebooks/deequ-constraints-suggesttions.ipynb)

[Verify suite](notebooks/deequ-verification-suite.ipynb)

[anomaly detection](notebooks/deequ-anomaly.ipynb)



