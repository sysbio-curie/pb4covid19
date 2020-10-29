This simulation is an example of how boolean models can be integrated into Paul Macklin's team PhysiCell simulation using PhysiBoSS, in order to integrate more mechanistic details into cell-specific intracellular models.

### Run in nanoHUB : https://nanohub.org/resources/pb4covid19

### Run in Binder : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vincent-noel/pb4covid19/master?filepath=pb4covid19.ipynb)

### Run locally with Docker and Docker-compose
```
git clone https://github.com/vincent-noel/pb4covid19
cd pb4covid19
docker-compose up -d
```
	
And then open your browser to this url : http://localhost:8888/notebooks/pb4covid19.ipynb

### Run locally with Docker
```
git clone https://github.com/vincent-noel/pb4covid19
cd pb4covid19
docker build -t pb4covid19 .
docker run -p 8888:8888 -d pb4covid19
```	

And then open your browser to this url : http://localhost:8888/notebooks/pb4covid19.ipynb
