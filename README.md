Convert docker-compose.yml to helm chart
```
kompose covert -c
```
Install from folder:
```
helm install test_apps ../test-chart -f test-chart/values.yml
```