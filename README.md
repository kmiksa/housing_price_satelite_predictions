# housing-price-predictor

[![Housing Prices with Satelite Images Presentation](https://youtu.be/S9r580x1kvU/0.jpg)](https://youtu.be/S9r580x1kvU "Housing Prices with Satelite Images Presentation")


## Build & quickstart

### Using docker-compose & Makefile
The simplest way to build and run the project is to type the following command in the terminal:

```shell
make build-and-run
```

After first build you can use `make jupyter` to omit the build phase.

### Using docker-compose
If the Makefile doesn't work you can use docker-compose commands:

```shell
docker-compose build
docker-compose up jupyter
```

After that open the browser on page http://localhost:9006/lab/tree/assignment.ipynb

### Using venv
If instead of docker you prefer to use venv:

```shell
python3 -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```


## Adding packages
If you would like to add & install packages simply put them in the [requirements.txt](requirements.txt) file and rerun the build/install step.ike to add & install packages simply put them in the requirements.txt file and rerun the build/install step.
