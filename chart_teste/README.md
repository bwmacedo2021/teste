## Install or Upgrade chart on GPA
### Variables
cluster-kafka:
- oms-dev-hlg

```helm3 upgrade --install akhq-${cluster-kafka} -f values-${cluster-kafka}.yaml . --namespace devops```

- ecom-dev

```
helm3 upgrade akhq-dev . --install --namespace dev2 -f values-ecom-dev.yaml --wait --debug
```
