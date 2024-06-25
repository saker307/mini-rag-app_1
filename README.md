# mini-rag-app
this is a minimal implimintation of the rag model for questioning and answring
## Requirments
python 3.8 or latter

### install python from pthon page [https://www.python.org/downloads/]
make python download now you have python in your pc 

## installation
***
### install requirements packages
pip install -r requirements.txt
***
### setup the environment variable
copy .env.example .env
set your environment variable in the ".env" file like "OPEN_API_KEY" value.

### run fast api server
uvicorn main:app --reload --host 0.0.0.0 --port 5000 