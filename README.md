## Usage

Before usage need to create network for correct dependencies work:
```shell
task network -v
```

To run all microservices and theirs dependencies in 
docker, use next command (twice due to migrations work logics):

```bash
task up -v
```

To stop all microservices and theirs dependencies, 
use next command:

```bash
task down -v
```

To clean up all created dirs and docker files, use next command:
```bash
task clean_up -v
```

## Tracing

To see tracing open
next [link](http://localhost:16686) in browser.
