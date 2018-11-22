###### 前提:k8s集群可用正常，网络干净 ##


### Sock Shop部署：

#### 下载所需文件

    $git clone   https://github.com/microservices-demo/microservices-demo.git


#### 创建命名空间并启动

    $kubectl create namespace sock-shop
    
    $kubectl apply -f complete-demo.yaml


至此：sock-shop部署完成。