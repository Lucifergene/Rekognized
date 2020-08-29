# Rekognized - A smart AI Based Image Classifier to identify variety of Images

[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

Website URL : https://rekognized.herokuapp.com/

Docker Image : <a href="https://hub.docker.com/r/avik6028/flask_cnn_deployment">avik6028/flask_cnn_deployment</a>

## Deployment Details

CI/CD Tool : GitHub Actions

* CI Pipeline : When new code changes are pushed, Automatically new Docker Image is built and pushed to DockerHub
* CD Pipeline : When Docker Image is re-built, the image is automatically pushed into the Heroku Container Registry
