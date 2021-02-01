## Google container registry
***
### 使用Github和Aliyun镜像仓库拉取Google镜像仓库镜像
#### 1.创建Dockerfile
```Dockerfile
FROM gcr.io/google-containers/image:version

MAINTAINER zhengwei <mail.zhengwei@qq.com>
```

#### 2.Aliyun镜像仓库配置Github连接地址构建拉取镜像

