# TuGraph_homework1
TuGraph图数据库作业1

## 1. TuGraph平台部署启动
### 部署步骤
本次实验使用TuGraph社区版，采用Docker方式部署：
1. 拉取TuGraph镜像：`docker pull tugraph/tugraph-runtime-centos7:4.4.0`
2. 启动容器，映射端口7071：
```bash
docker run -d -p 7071:7071 --name tugraph-demo tugraph/tugraph-runtime-centos7:4.4.0
![Uploading tugraph部署.png…]()
