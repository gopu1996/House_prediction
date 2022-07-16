Software and account Requirement.
Github Account
Heroku Account
VS Code IDE
GIT cli
GIT Documentation
Creating conda environment

conda create -p venv python==3.7 -y


...
conda activate venv/

...
pip install -r requirements.txt


BUID DOCKER IMAGE
...

docker build -t <image_name>:<tagname>


To list docker image
...

docker image


Run docker image
...

docker run -p 5000:5000 -e PORT =5000


