| NAME                   | PROMPT                       | DESCRIPTION                                  | EXAMPLE                                     |
|------------------------|------------------------------|----------------------------------------------|---------------------------------------------|
| app.yaml               | Add environment variables    | Define environment variables for the pod    | [Link](./yaml/app.yaml)                    |
| app-livenessProbe.yaml | Define liveness probe        | Specify settings for the liveness probe      | [Link](./yaml/app-livenessProbe.yaml)      |
| app-readinessProbe.yaml| Define readiness probe       | Specify settings for the readiness probe     | [Link](./yaml/app-readinessProbe.yaml)     |
| app-volumeMounts.yaml  | Define volume mounts         | Mount volumes to the pod                      | [Link](./yaml/app-volumeMounts.yaml)       |
| app-cronjob.yaml       | Define cron job command     | Set up a cron job to run a command           | [Link](./yaml/app-cronjob.yaml)            |
| app-job.yaml           | Define job command          | Create a one-time job to run a command       | [Link](./yaml/app-job.yaml)                |
| app-multicontainer.yaml| Add settings for containers | Define settings for multiple containers      | [Link](./yaml/app-multicontainer.yaml)     |
| app-resources.yaml     | Define resource limits      | Specify resource requests and limits         | [Link](./yaml/app-resources.yaml)         |
| app-secret-env.yaml    | Define secret environment   | Inject environment variables from a secret   | [Link](./yaml/app-secret-env.yaml)         |
