## Build container image

```bash
gcloud builds submit --tag gcr.io/gdg-cloud-tgu-2019-07-09/helloworld
```

## Deploy container image

```bash
gcloud beta run deploy --image gcr.io/gdg-cloud-tgu-2019-07-09/helloworld --platform managed
```