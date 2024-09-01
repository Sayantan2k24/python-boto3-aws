# Ubuntu 22.04

# install pip

sudo apt install python3-pip -y

# install python3-venv

sudo apt install python3.10-venv -y

# setup virtual environment

python3 -m venv venv

. venv/bin/activate

or

source venv/bin/activate

# install boto3

pip3 install boto3

# save dependecies in requirements.txt

pip3 freeze > requirements.txt

# install dependencies:

pip install -r requirements.txt

