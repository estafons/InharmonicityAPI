# steps

1) create envwrapper. Add to env start script:
- helpful env variables export
- setting docker on minikube

2) Add manifests for:
- Persistent Volume and Persistent Volume Claim

3) Setup postgres with helm chart

4) Create dummy app to check connectivity of components.

5) Create initial ORM.
- remember to "spoof" file names to unique.

6) Create basic structure of app.
- files saved properly on PV.
- audio files and associated annotations details saved properly on db.
- API for basic view of files saved.

7) Create dummy backend to simulate computation of inharmonicity.
- Ensure proper connection to the rest of the components.

8) Setup celery and rabbitMQ for dummy backend.

9) To be continued..