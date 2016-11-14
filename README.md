# SoundCloud

## What's included

- Python 2.7
- Jupyter Notebook
- Numpy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

### Requirements
To successfully spin up container please make sure that `Docker Engine` and `Docker Compose` are properly installed. If you have troubles please refer to [Docker homepage](https://www.docker.com/).

Verify if everything looks good by typing:

```bash
$ docker -v
Docker version 1.11.1, build 5604cbe

$ docker-compose -v
docker-compose version 1.7.1, build 0a9ab35
```

### Running container
Use created Docker Compose [file](docker-compose.yml) to provision new container. It will expose Notebook on port 8888 and mount `notebooks/` directory.

Inside directory:
```bash
$ docker-compose up -d
```

And in your browser proceed to `localhost:8888`.

### Data Scientist Challenge

The project contains 3 python notebook files, one for each question.

