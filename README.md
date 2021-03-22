# demo_appengine
GCP demo AppEngine deployment

This respository contain below scripts to demo the deployment of webservice code to GCP App Engine

Web app source : app.js (my version will randomly display image of sun/moon/star/mars/jupitor
Images folder : ./image/*.jpg (5 image files)
Deployment yaml : app.yaml

To deploy this to your GCP project.
1. Signon your GCP account.
2. git clone https://github.com/nelsonchui/demo_appengine
3. cd demo_appengine
4. gcloud app deploy
