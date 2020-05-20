Add secrets by using volume mount.
1) create a secret object
2) change the pod yaml, add volume mount to pod
3) exec the pod
4) check the mounted path for secrets


Use screts as env variable
1) create a secret object
2) change the pod yaml, add env variables and link to secrets
3) exec the pod
4) echo ${SECRET_USERNAME}