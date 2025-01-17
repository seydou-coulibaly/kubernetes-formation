# Troubleshooting

<walkthrough-tutorial-duration duration="55.0"></walkthrough-tutorial-duration>

## Description

In this exercise, you will troubleshoot a wordpress application deployed in the `application` namespace.

## Project selection and credentials

Please ensure your Google Cloud project is the one given by the trainer:

```sh
gcloud config set project XXX 
```

Now, you must retrieve the credentials of the kubernetes cluster:

```sh
gcloud container clusters get-credentials training-cluster --project ${GOOGLE_CLOUD_PROJECT} --zone europe-west1-b
```

## Instructions

With `kubectl`, investigate and fix the different resources.

Usefull commands: `kubectl get events`, `kubectl logs` and of course `kubectl describe`.

You have finished the exercise once the worpress application is correctly displayed in your web browser accessing the NodePort service.

## Congratulations

You have finished the Kubernetes fundamentals training!!

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>
