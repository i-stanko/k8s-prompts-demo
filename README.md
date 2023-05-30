# YAML Manifests Portfolio

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| app.yaml | Basic application manifest | The main manifest for deploying your application on Kubernetes | [Example](./yaml/app.yaml)
| app-livenessProbe.yaml | Liveness probe manifest | Defines the liveness probe for your application, Kubernetes will use this to know when to restart a container | [Example](./yaml/app-livenessProbe.yaml)
| app-readinessProbe.yaml | Readiness probe manifest | Defines the readiness probe for your application, Kubernetes will use this to know when your app is ready to serve traffic | [Example](./yaml/app-readinessProbe.yaml)
| app-volumeMounts.yaml | Volume mounts manifest | This manifest defines the storage volumes and mount points for your application | [Example](./yaml/app-volumeMounts.yaml)
| app-cronjob.yaml | CronJob manifest | This manifest defines a CronJob which runs tasks at specified intervals | [Example](./yaml/app-cronjob.yaml)
| app-job.yaml | Job manifest | This manifest defines a Job, a 'run to completion' application on Kubernetes | [Example](./yaml/app-job.yaml)
| app-multicontainer.yaml | Multi-container manifest | This manifest defines a Pod with multiple containers | [Example](./yaml/app-multicontainer.yaml)
| app-resources.yaml | Resources manifest | This manifest defines the resource requirements and limits for your application | [Example](./yaml/app-resources.yaml)
| app-secret-env.yaml | Secret environment variables manifest | This manifest defines Secret environment variables for your application | [Example](./yaml/app-secret-env.yaml)
