to run the app:

export FLASK_APP=run.py
flask run


to deploy the app to Google App Engine (flex):

gcloud app deploy -version dev 

# stop instance
gcloud app versions stop dev

# start instance
gcloud app versions start dev
