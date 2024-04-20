# kubectl-ai-primer
The repository contains some samples of *.yaml Kubernetes manifests created via kubectl-ai plugin.
----------
|Prompt|Manifesto|
|--|--|
|"please help me to create the yaml configuration file for the readiness probe"|apiVersion: v1<br>kind: Pod<br>metadata:<br>&nbsp;&nbsp;&nbsp;&nbsp;name: example-pod<br>spec:<br>&nbsp;&nbsp;&nbsp;&nbsp;containers:<br>&nbsp;&nbsp;&nbsp;&nbsp;- name: example-container<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;image: nginx<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ports:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- containerPort: 80<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;readinessProbe:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;httpGet:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;path: /<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;port: 80<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;initialDelaySeconds: 5<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;periodSeconds: 10<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;timeoutSeconds: 3|
 
