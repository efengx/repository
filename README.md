## setup minikube(本机运行测试环境)
(使用阿里云源安装minikube)[https://yq.aliyun.com/articles/221687]

## kubernetes command
```text
# 查看集群版本
minikube version
kubectl version

# 验证kubectl与集群是否正确通信
kubectl cluster-info

# 查看kubectl集群中所有的pods
kubectl get pods --all-namespaces

# 查看集群状态（web查看）
minikube deshboard

# 查看集群节点的详细信息
kubectl describe nodes
```

## docker images


## document
(kubernetes)[https://kubernetes.io/cn/docs/tasks/administer-cluster/kubelet-config-file/]

