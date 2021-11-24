
1. Write App (Flask, TensorFlow)
The code to build, train, and save the model is in the test folder.
Implement the app in main.py

2. Setup Google Cloud
Create new project
Activate Cloud Run API and Cloud Build API

3. Install and init Google Cloud SDK
https://cloud.google.com/sdk/docs/install

4. Dockerfile, requirements.txt, .dockerignore
https://cloud.google.com/run/docs/quickstarts/build-and-deploy#containerizing

5. Cloud build & deploy
gcloud builds submit --tag gcr.io/trashdetector/process_score_image_request
gcloud run deploy --image gcr.io/trashdetector/process_score_image_request --platform managed#   d e t e c t r o n d o c k e r  
 