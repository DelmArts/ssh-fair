# FAIR Tools Applied to Social Sciences and Humanities: A Study of Limitations

This code accompanies the Bachelor thesis "FAIR Tools Applied to Social Sciences and Humanities: A Study of Limitations". It consists of a Jupyter notebook, multiple data exports to ensure the results in the paper remain reproducible, and a `docker-compose.yml` to make deploying one of the FAIR analysis tools easy.


## Installation

Install Python dependencies:

```shell
pip install -r requirements.txt
```

If not working in VS Code or PyCharm:

```shell
pip install jupyterlab
jupyter lab
```

Run the provided Docker container:

```shell
docker compose up
```

Open `main.ipynb` in Jupyter Lab or VS Code/PyCharm and execute all cells.
