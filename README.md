# python3.6_dockerfile
这是一个构建python3.6环境的Dockerfile,其基础镜像为Alpine
## 如果需要使用pymysql则需要添加
```bash
  apk del openssl-dev \
	&& apk add --no-cache mariadb-connector-c-dev mysql-client
```
