# kubectl-ai-primer
The repository contains some samples of *.yaml Kubernetes manifests created via kubectl-ai plugin.
----------
Name|Prompt|Description|Example|
|--|--|--|--|
|app.yaml|create pod manifesto (application name = 'demo', image is nginx:lateReprompt: create pod manifesto (application name = 'demo', image is nginx:latest)|pod manifesto|[app.yaml](https://github.com/zeleneyabluko/kubectl-ai-primer/blob/main/yaml/app.yaml)|
|app-livenessProbe.yaml|create yaml config for a pod which runs a container with image registry.k8s.io/busybox, with liveness probe|yaml for liveness probe|[app-livenessProbe.yaml](https://github.com/zeleneyabluko/kubectl-ai-primer/blob/main/yaml/app-livenessProbe.yaml)|
|app-readinessProbe.yaml|please help me to create the yaml configuration file for the readiness probe|yaml for readiness probe|[app-readinessProbe.yaml](https://github.com/zeleneyabluko/kubectl-ai-primer/blob/main/yaml/app-readinessProbe.yaml)|
|app-volumeMounts.yaml|I want to add a durable volume and mount it to my container. please create app-volumeMounts.yaml for this|config for mounting a persistent volume into a container|[app-volumeMounts.yaml](https://github.com/zeleneyabluko/kubectl-ai-primer/blob/main/yaml/app-volumeMounts.yaml)|
|app-cronjob.yaml||||
|app-job.yaml|create a yaml config for job which will set up the db in the testing environment. It should take not more than 300 sec to run, with not more than 3 attempts|configuration for a one-time task|[app-job.yaml](https://github.com/zeleneyabluko/kubectl-ai-primer/blob/main/yaml/app-job.yaml)| 
|app-multicontainer.yaml||||
|app-resources.yaml||||
|app-secret-env.yaml||||
