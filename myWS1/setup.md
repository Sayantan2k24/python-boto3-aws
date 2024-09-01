# Ubuntu 22.04

# install pip

sudo apt install python3-pip -y

# setup virtual environment

python3 -m venv venv

. venv/bin/activate

or

source venv/bin/activate

# install boto3

pip install boto3

# save dependecies in requirements.txt

pip freeze > requirements.txt

# install dependencies:

pip install -r requirements.txt
