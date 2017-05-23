docker build -t gcr.io/vitalsource-gc/jenkins-jnlp-slave-gke:v13 -f Dockerfile.gradle .
gcloud docker -- push gcr.io/vitalsource-gc/jenkins-jnlp-slave-gke:v13
