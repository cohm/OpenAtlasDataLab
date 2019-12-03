# OpenAtlasDataLab
This repository contains a notebook setup (python+ROOT) that allows to easily play around with the open Run-2 data from the ATLAS experiment. This repo is based on another repository that specifically focused on measuring the Z boson in data from Run 1 of the LHC. Use together with jupyter with python3+ROOT available, e.g. via Docker image [cohm/pyroot-notebook](https://hub.docker.com/r/cohm/pyroot-notebook).

## Instructions
With Docker, start up the lab through running  
`docker run -p 3000:8080 kthatlas/opendatalab:SH2103`
and then going to `localhost:3000` in your browser.

This Docker image contains a snapshot of this repository, on top of [cohm/pyroot-notebook](https://hub.docker.com/r/cohm/pyroot-notebook).
The jupyter server is started when the image is run, and one can start working with the notebooks via a web browser. If you don't have access to a computer with Docker installed, you can use it in free four-hour sessions via [Play With Docker](https://labs.play-with-docker.com/)..
