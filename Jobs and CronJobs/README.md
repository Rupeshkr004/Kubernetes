This repository contains tutorials and examples related to Kubernetes Jobs and CronJobs..

## Rune the below commands to generate kubernetes cronjob YAML for

  kubectl create cronjob simplejob --image=cronjob --schedule="*/5 * * * *" --dry-run=client -o yaml > cronjob.yaml
