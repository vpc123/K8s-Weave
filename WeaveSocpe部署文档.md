###### 前提:k8s集群可用正常，网络干净 ##


### weaveScope部署：

定制相应版本的weaveScope的yaml文件：

    $curl https://cloud.weave.works/k8s/scope.yaml?k8s-version=1.6.7 -sL -o scope.yaml

当前目录下scope.yaml 拷贝文件到k8s集群中：

    $kubectl apply --namespace kube-system -f scope.yaml

