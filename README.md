
Instructions
------------
A dockerfile to build an image running the pre-filled Jupyter notebook of the challenge with the right environment is provided. The project needs to be downloaded first.

Build the docker image: 
```
$ docker build -t kickoff-ml-challenge .
```

Replace "~the-path" with the path to your local copy of the repository 

```
$ docker run -p 8888:8888 -v ~the-path:/home/jovyan/work kickoff-ml-challenge
```

You can now access to the notebook via:
```
http://127.0.0.1:8888 or just by following the console link
```
