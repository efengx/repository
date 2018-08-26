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
minikube dashboard

# 查看集群节点的详细信息
kubectl describe nodes

# 创建新的node
kubectl create -f [myName].yaml

# 验证节点
kubectl get all -l app=[myName]

# 删除制定node
kubectl delete all -l app=[myName]

# 阿里云ubuntu主机安装minikube
minikube start --vm-driver=none --registry-mirror=https://registry.docker-cn.com
```

## docker images


## document
(kubernetes)[https://kubernetes.io/cn/docs/tasks/administer-cluster/kubelet-config-file/]

