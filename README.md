## Usage

To run all microservices and theirs dependencies in 
docker, use next command (twice due to migrations work logics):

```bash
task docker_prod -v
```

To clean up all created dirs and docker files, use next command:
```bash
task clean_up -v
```
