
## Stack
![](https://img.shields.io/badge/Linux-informational?style=for-the-badge&logo=linux&logoColor=white&color=E95420)
![](https://img.shields.io/badge/Python-informational?style=for-the-badge&logo=python&logoColor=white&color=306998)
![](https://img.shields.io/badge/Docker-informational?style=for-the-badge&logo=docker&logoColor=white&color=0db7ed)
![](https://img.shields.io/badge/Kubernetes-informational?style=for-the-badge&logo=kubernetes&logoColor=white&color=326ce5)
![](https://img.shields.io/badge/Terraform-informational?style=for-the-badge&logo=terraform&logoColor=white&color=844fba)
![](https://img.shields.io/badge/Elastic-informational?style=for-the-badge&logo=elasticsearch&logoColor=white&color=66b5ae)
![](https://img.shields.io/badge/CI/CD-informational?style=for-the-badge&logo=github&logoColor=white&color=black)
![](https://img.shields.io/badge/CI/CD-informational?style=for-the-badge&logo=gitlab&logoColor=white&color=black)

## Manifest
```yaml
apiVersion: batch/v1
kind: Job
metadata:
  name: devops-engineer
spec:
  manualSelector: true
  parallelism: 1
  template:
    spec:
      containers:
      - name: nils-rotskyi
        image: human:notreallylatest
        command: ["work", "-n=10h"]
      restartPolicy: Always
  backoffLimit: 4
```
