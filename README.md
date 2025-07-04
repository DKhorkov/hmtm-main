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

## Grafana

To see metrics in Grafana open
next [link](http://127.0.0.1:8082) in browser.

## Prometheus

To see metrics in Prometheus open
next [link](http://127.0.0.1:8081/query) in browser.

## NATS

To see NATS monitoring open
next [link](http://localhost:8222) in browser.

## Redis

To stop Redis server, use next command:
```bash
redis-cli shutdown
```
